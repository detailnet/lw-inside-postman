# lw-inside-postman
[Postman Collection](https://www.getpostman.com/) for Louis Widmer Inside.

## Howto use
Following guide applies for:
 - [Postman REST client (Packaged App)](https://www.getpostman.com/)
 - [Postman REST client (Chrome extension)](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm)

###Howto access the collection data
Chose the one that best fits the testing situation you need:
 - Main Github repository | https://raw.githubusercontent.com/detailnet/lw-inside-postman/master/postman_collection.json
 - Own Github fork | https://raw.githubusercontent.com/{own-git-user}/lw-inside-postman/master/postman_collection.json
 - Local checkout trough protobox | http://lw-inside-postman.web01.detailnet.me/postman_collection.json

You can also access different branches on Github (replace "master" with the branch name)

###Import environments
 - Go to the environments manager window
  - Move the mouse pointer over the eye dropdown menu (top bar)
  - Click on "Manage environments"
 - Clik on "Import" button, choose all files in the project environments directory (all at once)

Note: There is no direct possibility to import from an url, but you can use your OS as wrapper. To do so enter an url instead of a file in the file selection window (e.g.: https://raw.githubusercontent.com/detailnet/lw-inside-postman/master/environments/development.json).

###Save tool cahnges back to project/repository
 - Move your mouse pointer over the collection name (left menu), click on "Share collection" icon.
 - Click on "Download" button.
 - Overwrite your local repository `{projects_dir}/lw-inside-postman/postman_collection.json` file.
 - Review changes vith your preferred editor and commit them trough GIT.

