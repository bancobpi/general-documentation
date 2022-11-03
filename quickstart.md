<p align="center">
  <img src="https://raw.github.com/bancobpi/general-documentation/master/static/quickstart_api.gif" alt="drawing" height="400" width="600" focus="false"/>
</p>

## Welcome to your Banco BPI workspace
<table>
<a href="https://bancobpi.stoplight.io/docs/general-documentation/ZG9jOjQ2MTY0ODI1-whitepaper"><img src="https://raw.github.com/bancobpi/general-documentation/master/static/quickstart_icone_api.gif" align="left" height="55" width="55" focus="false" hspace="20">
What are APIs and what are the guidelines for Banco BPI</a>
</table>

<table>
<a href="https://bancobpi.stoplight.io/docs/general-documentation/ZG9jOjQ2MTY0ODI2-stoplight-account"><img src="https://raw.github.com/bancobpi/general-documentation/master/static/quickstart_icone_stoplight.png" align="left" height="55" width="55" focus="false" hspace="20">
To be able to view documents and projects, it is necessary to create a Stoplight account.</a>
</table>

<table>
<a href="https://stoplight.io/api/v1/projects/cHJqOjEyMTg4Ng/images/l1WjBpb1lGA"><img src="https://raw.github.com/bancobpi/general-documentation/master/static/quickstart_icone_github.gif" align="left" height="55" width="55" focus="false" hspace="20"></a>
To be able to build APIs, it is necessary to create a GitHub account</a>
</table>



````json
BODY
{
  "taxIdentificationNumber": "123555999",
  "externalReference": "50138fbd-33a8-4b5e-b93f-91bd51681793",
  "fullName": "Bruno Rodrigues Gil",
}
````



```json
HTTP 200 OK

{
  "id": "973",
  "kind": "api-name.bancobpi.pt/v1/resource-name",
  "externalReference": "50138fbd-33a8-4b5e-b93f-91bd51681793",
  "taxIdentificationNumber": "123555999",
  "status": "active",
  "fullName": "Bruno Rodrigues Gil",
  "mec": "516611",
  "email": "email@bpi.pt",
  "displayName": "Laura Tiara",
  "_links": {
    "self": {
      "href": "https://examplehost/exampleapi/v1/example-resource/1"
    }
  }
}
```
