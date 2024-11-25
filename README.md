# OWASP Security Champions Guide
Using MKDocs to host our content (next to the OWASP project page) on https://securitychampions.owasp.org/.
Inspired by https://github.com/OWASP/API-Security and https://github.com/OWASP/Top10/tree/master/2021.

## Building a local copy on Windows
Install python
python3 -m pip install -r requirements.txt
python3 -m pip install mkdocs

### Testing locally
python3 -m mkdocs serve to run website on http://127.0.0.1:8000/

or

python3 -m mkdocs build to generate site content for deployment