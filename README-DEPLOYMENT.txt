USCN TRANSPARENCY WEBSITE — STATIC DEPLOYMENT

Upload the CONTENTS of this archive into the document root of transparency.uscn.org.uk (not a nested extra folder).

- index.html: homepage
- policies/index.html: policy directory, with approved-source PDFs where available
- documents/index.html: supporting working-document library (review before making publicly accessible)
- cameras/index.html: public camera directory
- cameras/view.html?id=CAMERA_ID: camera-specific public notice
- data/cameras.json: published camera records only; initially empty
- camera/: reserved for separate builder; README only

IMPORTANT: documents/files includes internal operational templates and workbook. If the whole package is placed in a publicly served directory, these files become publicly accessible. REMOVE or protect documents/files before public deployment unless you deliberately authorise public release. This package includes them because they were explicitly requested.

The full approved-source PDFs available in this session are POL-001, POL-002, POL-005 and LIA-001. POL-003 and POL-004 available locally only as draft DOCX, and POL-006 has approved wording in conversation but no verified final standalone file. Do not mislabel those draft source files as approved PDFs. Their descriptions are included; downloads are withheld until final source files are checked.

Company number shown: 17346373 (user-supplied branding). ICO registration number is not displayed in the footer.

To publish a camera, insert a record in data/cameras.json with fields id, area, status, purpose, coverage, safeguards, liveViewing, updated and published:true. Never include host addresses, secrets, private contact details or security configurations. JSON files are public.

No camera records are populated. No camera is presumed commissioned. No supplier contracts, legal assessments or policies are presumed published by packaging them.

Static web hosting is needed for fetch() of JSON. Opening via file:// may not work. The browser cannot write to ../data or other server files without a server-side API.

Update: Contact page and public footer include telephone numbers 0808 280 1223, 0330 520 1223, 0330 520 4085 (all three on contact page). Public sitemap.html, search engine sitemap.xml and robots.txt included. /camera/ excluded from sitemap and discouraged from indexing (robots.txt is not an access control).
