# OpenAPI YAML Mode

An Emacs major mode for [OpenAPI](https://github.com/OAI/OpenAPI-Specification) YAML files. OpenAPI YAML mode supports OpenAPI 2 and 3. OpenAPI 2 files are identical to the [Swagger](https://swagger.io/) 2 files.

OpenAPI YAML mode is based on [yaml-mode](https://github.com/yoshiki/yaml-mode), but uses a different strategy for syntax highlight that takes into consideration the OpenAPI specification.

OpenAPI YAML mode is under initial development and is not yet stable.

## Features

- Syntax highlight based on the OpenAPI specification (version 2 and 3).
- Very basic [Company](https://company-mode.github.io/) completion.
- [IMenu](https://www.gnu.org/software/emacs/manual/html_node/emacs/Imenu.html)
  for paths and operationIds.

## Complementary packages

- Swagger 2 validation can be added with the [flycheck-swagger-tools](https://github.com/magoyette/flycheck-swagger-tools) package.
