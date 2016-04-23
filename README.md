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

### Why So Much Preprocessor Support?

Honestly, people don't do this enough. Also, you should be using a preprocessor. If you're not by this day and age, consider checking one out and using it!

### Typography

Since the Ice Cream Sandwich release, Roboto has been the standard typeface on Android. Since Froyo, Noto has been the standard typeface on Android for all languages not covered by Roboto. Noto is also the standard typeface for all languages on Chrome OS.

### Language Categorization

Language scripts can be divided into three categories:

__English and English-like__: Latin (except Vietnamese), Greek, and Cyrillic scripts, supported by both Roboto and Noto. Roboto has been extended to completely cover all Latin, Greek, and Cyrillic characters as defined in Unicode 7.0. The number of supported characters has doubled from previous releases, from about 2000 to about 4000 characters.

__Tall__: Language scripts that require extra line height to accommodate larger glyphs, including South and Southeast Asian and Middle-Eastern languages, like Arabic, Hindi, Telugu, Thai, Vietnamese. Noto supports these languages with two weights.

__Dense__: Language scripts that require extra line height to accommodate larger glyphs, including Chinese, Japanese, and Korean. Noto supports these languages with seven weights.

### Typeface

#### Roboto

Roboto has been refined extensively to work across the wider set of supported platforms. It is slightly wider and rounder, giving it greater clarity and making it more optimistic.

![Examples of Roboto](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7SW9CUzR4MnRpOTg/style_typography_roboto1.png)

#### Roboto font weights

Roboto has six weights: Thin, Light, Regular, Medium, Bold, and Black.


