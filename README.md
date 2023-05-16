# AnnoTree Landing Page

This is project is based on [Freelancer landing page](https://startbootstrap.com/template-overviews/freelancer/)

#Installing and Updating

Making sure you have node6

Gulp-sass, part of the build tool here works well with node 6.x

use `node --version` to check your version, if different, proceed to https://github.com/ekalinin/nodeenv to install nodeenv that customizes your node environment. Specifically:

```
sudo easy_install nodeenv
# do NOT use root user now, otherwise script will be stuck
nodeenv node6 --node=6.14.4
. node6/bin/activate
# you have node 6 now
node --version
# should say 6.14.4
npm install
node node_modules/gulp/bin/gulp.js
# the default job compiles all SCSS files and minifies javascript, you should be good to go
```

Running in dev mode, real time update in browser

```
node node_modules/gulp/bin/gulp.js dev
```

Making production files

```
node node_modules/gulp/bin/gulp.js dev
```

## Linking with main app

Symlink in this folder app/ to the public/ folder in annotree-frontend, so that all requests to `<base url>/app/` gets redirected

## Copyright and License

Copyright 2013-2018 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-freelancer/blob/gh-pages/LICENSE) license.
# AnnoTreeLanding
