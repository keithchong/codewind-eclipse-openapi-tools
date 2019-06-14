# codewind-eclipse-openapi-tools
OpenAPI Tools for Eclipse and Codewind

Generate client and server stubs, and HTML documentation from OpenAPI definitions.  The tools work for both Eclipse IDE for Java EE Developers with or without Codewind for Eclipse.

## Getting started

1. Download and install the latest [Eclipse IDE for Java EE Developers](https://www.eclipse.org/downloads/packages/release/) or use an existing installation. Note that if using these tools with Codewind, the earliest supported version of the Eclipse IDE is 4.11.0 (2019-03).
2. (Optional) Install [Codewind from the Eclipse Marketplace](https://marketplace.eclipse.org/content/codewind).
3. Install the [OpenAPI Tools for Eclipse and Codewind from the Eclipse Marketplace](https://marketplace.eclipse.org/content/codewind).

## How to use
1. Invoke the context menu on any existing workspace projects or any workspace OpenAPI definition files (openapi.yaml) from the Package Explorer or Project Explorer views.
2. If Codewind is installed, the context menu generator actions are available in the Codewind Explorer view
3. Ensure at least one OpenAPI definition is in the project
4. Select an action to generate the client or server stubs or HTML documentation
5. Fill in information that is displayed from the wizard   
6. After generation, edit .openapi-generator-ignore to ensure subsequent code generation does not overwrite custom code

## Features
- Generate API clients in any of the supported [languages/frameworks](https://github.com/OpenAPITools/openapi-generator#overview)
- Generate server stubs in any of the supported [languages/frameworks](https://github.com/OpenAPITools/openapi-generator#overview)
- Generate HTML documentation from an OpenAPI definition file.
