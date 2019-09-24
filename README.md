# RavimoShark API Contracts OpenAPI Specification

> The **main repository** is hosted in [gitlab.com/ravimosharksas](https://gitlab.com/ravimosharksas/apis/contract/documentation.git) but it is automatically mirrored to [github.com/RavimoShark](https://github.com/RavimoShark/apis-contract-documentation.git), [github.com/singletonsd](https://github.com/singletonsd/ravimosharksas-apis-contract-documentation.git), [github.com/patoperpetua](https://github.com/patoperpetua/ravimosharksas-apis-contract-documentation.git), [gitlab.com/singletonsd](https://gitlab.com/singletonsd/ravimosharksas/apis/contract/documentation.git) and to [gitlab.com/patoperpetua](https://gitlab.com/patoperpetua/ravimosharksas-apis-contract-documentation.git), [github.com/patoperpetua](https://github.com/patoperpetua/ravimosharksas-apis-contract-documentation.git). If you are in the Github page it may occur that is not updated to the last version.

## PROJECT INFORMATION

<img src="http://online.swagger.io/validator?url=https://ravimosharksas.gitlab.io/apis/contract/documentation/openapi.json">

Swagger documentation of global API. See HTML documentation in
[https://ravimosharksas.gitlab.io/apis/contract/documentation](https://ravimosharksas.gitlab.io/apis/contract/documentation)

## USAGE

- Starts the development server: `npm start`
- Bundles the spec and prepares web_deploy folder with static assets: `npm run build`
- Validates the spec: `npm test`
- Deploys docs to GitHub Pages: `npm run gh-pages`
- Run swagger-repo scripts locally: `npm run swagger-repo`
- Run create-openapi-repo scripts locally: `npm run create-openapi-repo`

## DOCUMENTATION

You can create the following folders here:

- `schemas` - reusable [Schema Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#schemaObject)
- `responses` - reusable [Response Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#responseObject)
- `parameters` - reusable [Parameter Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#parameterObject)
- `examples` - reusable [Example Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#exampleObject)
- `headers` - reusable [Header Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#headerObject)
- `requestBodies` - reusable [Request Body Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#requestBodyObject)
- `links` - reusable [Link Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#linkObject)
- `callbacks` - reusable [Callback Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#callbackObject)
- `securitySchemes` - reusable [Security Scheme Objects](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md#securitySchemeObject)

## LINKS

- [Reference Documentation (ReDoc)](https://ravimosharksas.github.io/apis/)
- OpenAPI Raw Files: [JSON](https://ravimosharksas.gitlab.io/apis/global/documentation/openapi.json) [YAML](https://ravimosharksas.gitlab.io/apis/global/documentation/openapi.yaml)
- [ReDoc Repository Example](https://github.com/Rebilly/RebillyAPI)

## CONTRIBUTING

Contributions to this repository are very welcome.

To contribute, please fork this repository on GitLab and send a pull request with a clear description of your changes. If appropriate, please ensure that the user documentation in this README is updated.

If you have submitted a PR and not received any feedback for a while, feel free to [ping me on Twitter](https://twitter.com/patoperpetua) [or find me on facebook](https://www.facebook.com/pato.arg)

## TODO

- [ ] Config tool to generate models diagram.
- [X] Config client libraries on commit.
- [X] Upload html documentation to gitlab pages.
- [ ] Upload html documentation to servers.
- [ ] Use scripts from remote repository.
- [ ] Gitlab ci-cd template from remote repository.
- [X] Split swagger.yaml into multiple files.
- [X] Use [ReDoc](https://github.com/Redocly/redoc) documentation framework.

----------------------

© [Singleton SD](http://www.singletonsd.com), France, 2019.
