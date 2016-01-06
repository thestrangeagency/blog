# The Strange Agency Development Blog

### Development

```
$ git clone https://github.com/thestrangeagency/blog.git
$ cd blog
$ bower install
$ npm install
$ gem install jekyll
$ gulp serve
```

### Deployment

Build the distribution build:

```
$ gulp
```

Check the distribution build:

```
$ gulp serve:dist
```

Deploy to Github Pages:

```
$ gulp deploy
```