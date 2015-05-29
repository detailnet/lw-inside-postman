# lw-inside-postman
[Postman Collection](https://www.getpostman.com/) for Louis Widmer Inside.

## Howto use
Following guide applies for:
 - [Postman REST client (Packaged App)](https://www.getpostman.com/)
 - [Postman REST client (Chrome extension)](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm)

###Howto access the collection data
Choose the one that best fits the testing situation you need:
 - Main GitHub repository | https://raw.githubusercontent.com/detailnet/lw-inside-postman/master/collections/default.json
 - Own GitHub fork | https://raw.githubusercontent.com/{own-git-user}/lw-inside-postman/master/collections/default.json
 - Local checkout trough protobox | http://lw-inside-postman.collections.web01.detailnet.me/default.json

> You can also access different branches on GitHub (replace `master` with the branch name)

###Import environments
 - Go to the environments manager window
  - Move the mouse pointer over the eye dropdown menu (top bar)
  - Click on "Manage environments"
 - Click on "Import" button, choose all files in the project environments directory (all at once)

> There is no direct possibility to import from an url, but you can use your OS as wrapper. 
> To do so enter an url instead of a file in the file selection window (e.g.: https://raw.githubusercontent.com/detailnet/lw-inside-postman/master/environments/development.json).

###Setup global variables
We use global variables to store data that is your own and must not be shared with others.

Currently whe support following global variables:
 - `credential_application_id`: API application ID _(used for production environments)_
 - `credential_application_key`: API application Key _(used for production environments)_

To set up global variables:
 - Go to the environments manager window
  - Move the mouse pointer over the eye dropdown menu (top bar)
  - Click on "Manage environments"
 - Click on "Globals" button
 - Add the variables

> API credentials for Louis Widmer Inside are stored at [3scale](https://detailnet-admin.3scale.net)

###Save tool changes back to project/repository
 - Move your mouse pointer over the collection name (left menu), click on "Share collection" icon.
 - Click on "Download" button.
 - Overwrite your local repository `{projects_dir}/lw-inside-postman/collections/default.json` file.
 - Review changes with your preferred editor and commit them trough Git.
