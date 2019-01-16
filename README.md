# heroku-buildpack-imagemagick-policy

A buildpack to install ImageMagcik with less restrictive policy limits on Heroku.
Sets higher memory and disk limits than the default ImageMagick / Heroku policies.

This is meant to be used in conjunction with other ImageMagick buildpacks.

**Usage**
`$ heroku buildpacks:add https://github.com/monteverdetico/heroku-buildpack-imagemagick-policy --index 1 --app <your app>
`
