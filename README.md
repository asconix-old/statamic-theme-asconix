# Asconix theme for Statamic 2

This repository contains a Statamic 2 theme that is based on the default theme [Redwood](https://statamic.com/blog/redwood).

To develop on the Asconix theme and extend it requires few packages to be installed. The toolchain uses the automating toolkit [Gulp](http://gulpjs.com) extensively, which requires NodeJS and NPM being installed. Being on macOS install NodeJS via Homebrew:

```nohighlight
$ brew info node
```

Next check the NodeJS and NPM versions:

```nohighlight
$ node -v
```

In our case we use Node 9.3.0. Also check the version of NPM:

```nohighlight
$ npm -v
```

... which in my case is version 5.6.0.

Next install Gulp itself:

```nohighlight
$ cd statamic-theme-asconix
$ npm install gulp-cli -g
$ npm install gulp -D
```

Finally install all dependencies:

```nohighlight
$~ npm install
```

Finally we launch gulp to trigger recompile runs automatically everytime, when e.g. the underlying SASS files have been changed:

```nohighlight
$ gulp watch
```

