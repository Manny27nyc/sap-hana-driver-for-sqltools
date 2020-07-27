[![CircleCI](https://circleci.com/gh/sap-staging/sap-hana-driver-for-sqltools.svg?style=svg)](https://circleci.com/gh/sap-staging/sap-hana-driver-for-sqltools)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![DependentBot](https://api.dependabot.com/badges/status?host=github&repo=SAP/sap-hana-driver-for-sqltools)](https://dependabot.com/)

# SAP HANA Driver for SQLTools
A Visual Studio Code extension which extends [SQLTools extension](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools), with a driver to work with SAP HANA Database. It supports Tables and Views and running queries on a SAP HANA Database.

## Installation

### From the VS Code Marketplace

In the [SAP HANA Driver for SQLTools](https://marketplace.visualstudio.com/items?itemName=SAPOSS.sap-hana-driver-for-sqltools) VS Code marketplace page, click **Install**.

### From GitHub Releases

1. Go to [GitHub Releases](https://github.com/sap/sap-hana-driver-for-sqltools/releases).
2. Search for the `.vsix` archive under `sap-hana-driver-for-sqltools\@x.y.z` releases. (Replace `x.y.z` with the desired version number.)
3. Follow the instructions for installing an extension from a `.vsix` file in the [VSCode's guide](https://code.visualstudio.com/docs/editor/extension-gallery#_install-from-a-vsix).

## Usage

### Creating connection schema for the assistant

We are using `@rjsf/core` to render the forms, so in order to add you driver to the connection assistant,
edit `connection.schema.json` and `ui.schema.json`.

See https://react-jsonschema-form.readthedocs.io/en/latest/ for more instructions.

## Support

Please open [issues](https://github.com/SAP/sap-hana-driver-for-sqltools/issues) on github.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved.
This file is licensed under the Apache Software License, v. 2 except as noted otherwise in the [LICENSE file](./LICENSE).


