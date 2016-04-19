# Material Typography
Typography based on Google's Material Design Standard

Available in CSS, LESS, SASS, SCSS, and Stylus.

### Install Instructions

#### NPM

```
npm i --save material-typography
```

#### Bower

```
bower install material-typography
```

Or simply download the `.zip` and place it in your project folder wherever you'd like.

_*Please Note*_ that the initial directory is not required for this project to work. Your entry point can be simply one of the css, less, sass, scss, or stylus directories.

### Usage Instructions

There should be no reason to compile each of the less, sass, scss, and stylus versions individually to use this package. Simply include `typography.css|less|sass|scss|styl` in your primary stylesheet and let your compiler compile *only* your primary stylesheet. This will concatenate `material-typography` into your primary stylesheet at your desired output location.
#### Beginner

To use `material-typography` in your project, using basic CSS, simply use the `@import url()` statement where `typography.min.css` is located.

#### Intermediate

When compiling your primary stylesheet with `material-typography` included, install the associated preprocessor using `npm` or some other package manager, then compile. All preprocessed libs are identical upon compile, and the basic CSS will function just the same. Using a preprocessor is not required.

#### Advanced

If you're using a service like `Webpack` or `Babel`, compiles will work the same. You'll just have a pseudo-location since Webpack handles things in memory, rather than on-disk. So just be aware of the output location set in your `.babelrc` or `webpack.config.js`.
