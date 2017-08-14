# Cloud Foundry Rename Resource

An output only resource (at the moment) that will delete an application from cloud foundry.

## Source Configuration

* `api`: *Required.* The address of the Cloud Controller in the Cloud Foundry
  deployment.
* `username`: *Required.* The username used to authenticate.
* `password`: *Required.* The password used to authenticate.
* `organization`: *Required.* The organization to push the application to.
* `space`: *Required.* The space to push the application to.
* `skip_cert_check`: *Optional.* Check the validity of the CF SSL cert.
  Defaults to `false`.

## Behaviour

### `out`: Rename an application

Deletes an application in Cloud Foundry.

#### Parameters

* `application`: *Required.* The name of the application.
