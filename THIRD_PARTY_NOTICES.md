# Third-party software and services

MailFlow Lite application source is supplied under the MIT license in `LICENSE`. The following projects remain the property of their respective contributors and retain their own licenses. Runtime wheels include their upstream notices; the executable build specification also collects metadata/notices for its main dependencies.

| Component | Purpose / upstream |
|---|---|
| Python | Runtime — https://www.python.org/psf/license/ |
| Tcl/Tk and Tkinter | Native desktop foundation — https://www.tcl.tk/software/tcltk/license.html |
| CustomTkinter | Rounded light-themed widgets — https://github.com/TomSchimansky/CustomTkinter |
| SQLite | Local transactional database — https://www.sqlite.org/copyright.html |
| Pandas | Excel/CSV data processing — https://pandas.pydata.org/ |
| OpenPyXL | XLSX reading and sample workbook generation — https://openpyxl.readthedocs.io/ |
| defusedxml | DTD/entity-safe XLSX XML preflight — https://github.com/tiran/defusedxml |
| APScheduler 3.x | Local interval job scheduling — https://github.com/agronholm/apscheduler |
| email-validator | Syntax and normalized-address validation — https://github.com/JoshData/python-email-validator |
| Google API Python client | Official Gmail API client — https://github.com/googleapis/google-api-python-client |
| google-auth | Google OAuth credential/identity handling — https://github.com/googleapis/google-auth-library-python |
| google-auth-oauthlib | Desktop browser/PKCE OAuth flow — https://github.com/googleapis/google-auth-library-python-oauthlib |
| google-auth-httplib2 / httplib2 | Authorized Gmail API HTTP transport — https://github.com/googleapis/google-auth-library-python-httplib2 and https://github.com/httplib2/httplib2 |
| Requests / OAuthlib / requests-oauthlib | TLS HTTP and OAuth plumbing — https://requests.readthedocs.io/ and https://github.com/requests/requests-oauthlib |
| tzdata / IANA timezone data | Asia/Kolkata on Windows — https://pypi.org/project/tzdata/ |
| Pillow | CustomTkinter image support — https://python-pillow.org/ |
| pytest | Development-only tests — https://pytest.org/ |
| PyInstaller | Optional Windows executable bundler — https://pyinstaller.org/en/stable/license.html |

Transitive dependencies (such as certifi, cryptography, NumPy, dateutil, tzlocal, darkdetect, protocol buffers, Google API Core, IDNA and DNS libraries) are resolved by pip and retain their upstream licenses. These are free/open-source tools; optional bundling must preserve the notices relevant to the versions actually installed. PyInstaller's license contains a bootloader exception permitting distribution of bundled applications under their own license; review the upstream license when distributing a build.

Windows and DPAPI are existing operating-system facilities, not an additional paid service bundled by this project. Gmail/Google OAuth and business email providers are **external services governed by their own terms**, not application source covered by this MIT license. No Google affiliation, verification status or delivery guarantee is implied. Existing Windows/email subscriptions and internet access are outside the ₹0 development-tools budget.
