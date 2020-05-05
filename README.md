# object-store-specs
Specifications for the Object Store Module (aka multimedia)

This repository aim is to collect and document the different requirements (what the module should do) and the specifications (how the module should do it). The scope is limited to what the module should do to be DINA compliant and should not target a specific institution. 

Requirements/Specifications are recorded as [Issues](https://github.com/DINA-Web/object-store-specs/issues).

# API Specifications
Rendered version: https://dina-web.github.io/object-store-specs/

JSON-Schemas: https://github.com/DINA-Web/object-store-specs/tree/json-schema/schema

# JSON Schema to GitHub Pages

[Travis CI](https://travis-ci.org/) is configured to generate a new version of the rendered API specifications on each push. It is using [json-schema2adoc](https://github.com/AAFC-BICoE/json-schema2adoc) to transform the JSON Schemas of that repository into asciidoc files that are then included by the [API specification file](https://github.com/DINA-Web/object-store-specs/blob/json-schema/object-store-rest-api.adoc). A final conversion will generate an HTML that is pushed to GitHub pages.