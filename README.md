# Trying out standard UV with an open manifest from the National Archives in Sweden
The UV-package that is used is from the master branch and not the latest release.  

To install
- clone the repo
- run npm install
- use http-server (you may need to install http-server globally first)

If there is a problem loading files it could depend on a change of version. Right now the exact version is referenced in the html files.
This problem could be managed by a gulp task but that would be kind of overkill.
I could also use express instead of http-server.

Note that the app.html page in the root folder does not seem to be used since UV loads the one on the same folder as the embed.js file in the index.html.

