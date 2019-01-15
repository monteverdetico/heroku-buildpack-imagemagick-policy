# heroku-buildpack-imagemagick-policy

A small buildpack to set less restrictive policy limits for ImageMagick on Heroku.
Sets higher memory and disk limits than the default ImageMagick / Heroku policies.


**Usage**
`$ heroku buildpacks:add https://github.com/monteverdetico/heroku-buildpack-imagemagick-policy --index 1 --app <your app>
`
