# rathskeller

Rathskeller is a fledgeling [ActivityPub](https://www.w3.org/TR/activitypub) implementation geared around ease of deployement to AWS and minimal hosting costs and maintenance.

## Deployment

TODO - Need code to deploy first...

## More Information

### Initial Goals
* Backend is modular, optimized for deployment as multiple AWS Lambda functions.
* Frontend can be deployed as a static website.

### Down the Road
If this project survives my inability to maintain focus on side projects and lack of free time, I would eventually like to move it towards:
* Fully compliant ActivityPub server.
* Federation support with other ActivityPub implementations.
* Generic client that can be pointed at other ActivityPub implementations.

### Raison d'Etre
I want a social network I can self-host for family and friends to share things within a fairly limited circle.

The focus should be on serving the users and while imposing minimal hosting costs and maintenance requirements.

All data should be backup and restore friendly.  Users should be able to get all data they can see in the system in a portable format for offline viewing or migration to another service.

Access should be secure, private by default.
