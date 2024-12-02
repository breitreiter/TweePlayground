This is a Twine/Twee project.

It is built using tweego - https://www.motoslave.net/tweego/docs/

It's using the SugarCube 2 format - https://www.motoslave.net/sugarcube/2/docs/#introduction

The entire repo is downloaded into the build directory at build time. tweego is configured to compile all contents of /src into /index.html. This means twee files can reference static files in the repo using the file's normal path in the repo (as those references get built into /index.html).
