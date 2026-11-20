# mini-portwood

A small document generator for Salesforce, built step by step while learning developer workflows. It's modelled on [Portwood](https://github.com/Portwood-Global-Solutions/Portwood), a free, open-source Salesforce package that turns records into PDF, Word, Excel and PowerPoint documents.

Status: setting up the repository (Module 2).

## What it will do

- Store document templates in a custom object
- Merge `{FieldName}` tags with a record's data
- Render the result as a PDF and save it as a File on the record
- Run from a button on the record page or from a Flow

The plan, module by module, is in [docs/roadmap.md](docs/roadmap.md).

## How changes get in

Every change to `main` arrives through a pull request from a short-lived branch. A ruleset on `main` enforces it.

## License

MIT. See [LICENSE](LICENSE).
