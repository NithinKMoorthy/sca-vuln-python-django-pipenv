# sca-vuln-python-django-pipenv

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** PyPI (Pipfile + requirements.txt)

## Expected findings (non-exhaustive)
- Django 2.2.0: CVE-2019-12308, CVE-2019-14234, CVE-2021-35042, many more
- djangorestframework 3.9.0: CVE-2020-25626
- sqlparse 0.4.1: CVE-2021-32839, CVE-2023-30608
- lxml 4.6.2: CVE-2021-28957
- numpy 1.19.0: CVE-2021-33430
