# Titanic Learning from Disaster

Titanic Learning from disaster

## Project Structure

```text
kaggle-titanic
|-- bin/                         # CLI scripts
|-- notebooks
|   |-- *.ipynb                  # Jupyter notebooks
|   `-- my_nb_path.py            # Imported by *.ipynb to treat src/ as PYTHONPATH
|-- requirements/                # Dependencies required by this project
|-- src                          # Python modules developed in this project
|   |-- titanic-pckg
|   `-- my_nb_color.py           # Imported by *.ipynb to colorize their outputs
|-- tests/                       # Unit tests
|-- MANIFEST.in                  # Required by setup.py
|-- setup.py                     # To pip install titanic-pckg

# Miscellaneous files
|-- .editorconfig                # Editor config (for IDE / editor that support this)
|-- .gitattributes               # Files that Git must give special treatments
|-- .gitignore                   # Git ignore list
|-- .pre-commit-config.yaml      # Precommit hooks
|-- LICENSE                      # License
|-- README.md                    # Template document
|-- pyproject.toml               # Settings for select Python toolchains
`-- tox.ini                      # Settings for select Python toolchains
```

## Credits

This project was initialized by Your name (or your organization/company/team) using:

```bash
cookiecutter https://github.com/aws-samples/python-data-science-template
```

## License

This library is licensed under the No license file.
