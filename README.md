# Python client and module for Vulnerability-Lookup

[PyVulnerabilityLookup](https://github.com/vulnerability-lookup/PyVulnerabilityLookup), a Python library to access
[Vulnerability-Lookup](https://github.com/vulnerability-lookup/vulnerability-lookup) via its REST API.

PyVulnerabilityLookup allows you to fetch vulnerabilities, create comments, bundles, sightings, and more.


## Installation

```bash
pip install pyvulnerabilitylookup
```

## Usage

### Command line

You can use the `vulnerability_lookup` command:

```bash
$ vulnerability_lookup -h
usage: vulnerability_lookup [-h] --url URL (--redis_up | --vulnerability VULNERABILITY)

Query a thing.

options:
  -h, --help            show this help message and exit
  --url URL             URL of the instance.
  --redis_up            Check if redis is up.
  --vulnerability VULNERABILITY
                        Get a vulnerability.
```

### Library

See [API Reference](https://pyvulnerabilitylookup.readthedocs.io/en/latest/api_reference.html)
