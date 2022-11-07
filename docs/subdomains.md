# Subdomains
<div>
<a href="https://sutton-signwriting.io/" class="btn btn-primary disabled" role="button">Apex Domain</a>
<a href="https://www.sutton-signwriting.io/" class="btn btn-primary" role="button">www</a>
<a href="https://donate.sutton-signwriting.io/" class="btn btn-primary" role="button">donate</a>
<a href="https://token.sutton-signwriting.io/" disabled class="btn btn-primary disabled" role="button">token</a>
<a href="https://cloud.sutton-signwriting.io/" disabled class="btn btn-primary disabled" role="button">cloud</a>
<a href="https://archive.sutton-signwriting.io/" disabled class="btn btn-primary disabled" role="button">archive</a>
<a href="https://legacy.sutton-signwriting.io/" disabled class="btn btn-primary disabled" role="button">legacy</a>
</div>


| Subdomain  | Purpose            | Status                   |
|:-----------|:-------------------|:-------------------------|
|            | Apex Domain        | Forward to www subdomain |
| www        | Static Information | Live using github pages  |
| donate     | Accept Donations   | Secure payment by square |
| token      | Authentication     | Under Development        |
| cloud      | Data Services      | Under Development        |
| archive    | Data Archives      | Under Development        |
| legacy     | Historical Source  | Under Development        |


## Apex Domain

The Apex Domain of Sutton-SignWriting.io is not available yet.
The DNS entry points to the Sutton SignWriting flagship server.
The server configuration needs a definition, redirect, and security certificates.

* [https://sutton-signwriting.io](https://sutton-signwriting.io)  

## www

The www subdomain of Sutton-SignWriting.io is live on GitHub pages.
This subdomain hosts the main documentation for Sutton SignWriting along with various project sites.

* [https://www.sutton-signwriting.io](https://www.sutton-signwriting.io)
* [https://www.sutton-signwriting.io/core](https://www.sutton-signwriting.io/core)
* [https://www.sutton-signwriting.io/font-db](https://www.sutton-signwriting.io/font-db)
* [https://www.sutton-signwriting.io/font-ttf](https://www.sutton-signwriting.io/font-ttf)
* [https://www.sutton-signwriting.io/sgnw-components](https://www.sutton-signwriting.io/sgnw-components)
* [https://www.sutton-signwriting.io/signmaker](https://www.sutton-signwriting.io/signmaker)

## token

The token subdomain is used to provision and validate Json Web Tokens for Sutton SignWriting authentication.
JWT is used to validate access to routes using header authentication and URI.
Use "jti" to pass via URL query parameter.

* [https://jwt.io](https://jwt.io)
* [RFC 7519](https://datatracker.ietf.org/doc/html/rfc7519)

## cloud

The cloud subdomain is under active development.
The cloud will collect and organize writing by country, language, and channel.

The source code is on GitHub.

* [https://github.com/sutton-signwriting/cloud-maker](https://github.com/sutton-signwriting/cloud-maker)

## archive

The archive subdomain will be used to host large datasets by group and project.

Project data will be divided between:

* rawdata - starting point
* sourcedata - nicely formatted TSV and JSON data
* derivatives - useful prebuilt by pipeline

## legacy

The legacy subdomain will be used to host historical websites and documents.
