# CyGlobs-Python-Web-Framework

CyGlobs Python Client Server Framework
A lightweight Python client/server framework built around this methodology:

Comparators
Inverse Operators
Contingency Planning
Level Of Indirection
Best Practices
Architecture
Methodology	Framework Role
Comparators	Validate protocol versions and payload contracts.
Inverse Operators	Map abstract client operations to server-side handlers.
Contingency Planning	Provide retries, timeouts, safe fallback envelopes, and error handling.
Level Of Indirection	Separate transport, protocol, service logic, configuration, and tests.
Best Practices	Type hints, dataclasses, Pydantic envelopes, tests, and clear entry points.
Requirements
Recommended Python versions:

Python 3.10
Python 3.11
Python 3.12
Check your version:

python --version
The requirements.txt file is in the root directory of this repository:

CyGlobs-Python-Framework-For-Full-Stack-Developers/
├── requirements.txt
├── server.py
├── client.py
├── framework/
└── tests/
Install on Windows
From the repository root:

python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
