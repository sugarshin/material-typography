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

### Usage Instructions

There should be no reason to compile each of the less, sass, scss, and stylus versions individually to use this package. Simply include `typography.css|less|sass|scss|styl` in your primary stylesheet and let your compiler compile *only* your primary stylesheet. This will concatenate `material-typography` into your primary stylesheet at your desired output location.

# Typography

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


