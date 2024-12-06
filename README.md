# Python Package Server
This is a GitHub pages site,
serving as a Python Package Server.

[PEP 503](https://peps.python.org/pep-0503/)

## Usage
To use packages hosted on this Python Package Server,
add `--extra-index-url https://egoossen.github.io/python-package-server/`
to the `pip` command.

## Example Usage
`pip install example_package_egoossen --extra-index-url https://egoossen.github.io/python-package-server/`

`pip install example_package_egoossen==0.0.4 --extra-index-url https://egoossen.github.io/python-package-server/`

`pip install --extra-index-url https://egoossen.github.io/python-package-server/ example_package_egoossen`

`pip install --extra-index-url https://egoossen.github.io/python-package-server/ example_package_egoossen==0.0.4`
