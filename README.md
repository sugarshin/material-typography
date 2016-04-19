# Material Typography
Typography based on Google's Material Design Standard

Available in CSS, LESS, SASS, SCSS, and Stylus.

To use CSS, simply use

```
@import /path/to/material-typography/css/typography.min.css
```

In your primary stylesheet.

### Install Instructions

#### NPM

```
npm i --save material-typography
```

#### Bower

```
bower install material-typography
```

### Special Note

If you just want to use a compiled version of one of the preprocessors, use `npm run` followed by the name of the desired preprocessor, followed by `:b`

For example

```
npm run stylus:b
```

Which will compile the source and place them in `/build/typography.min.css`. All compiles should look and function the same, however, the normal CSS version will look significantly different, but will function the same.
