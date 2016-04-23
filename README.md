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

Or simply download the `.zip` and place it in your project folder wherever you'd like, then include your flavor of `typography` in your primary stylesheet.

# Typography

Since the Ice Cream Sandwich release, Roboto has been the standard typeface on Android. Since Froyo, Noto has been the standard typeface on Android for all languages not covered by Roboto. Noto is also the standard typeface for all languages on Chrome OS.

### Language Categorization

Language scripts can be divided into three categories:

__English and English-like__: Latin (except Vietnamese), Greek, and Cyrillic scripts, supported by both Roboto and Noto. Roboto has been extended to completely cover all Latin, Greek, and Cyrillic characters as defined in Unicode 7.0. The number of supported characters has doubled from previous releases, from about 2000 to about 4000 characters.

__Tall__: Language scripts that require extra line height to accommodate larger glyphs, including South and Southeast Asian and Middle-Eastern languages, like Arabic, Hindi, Telugu, Thai, Vietnamese. Noto supports these languages with two weights.

__Dense__: Language scripts that require extra line height to accommodate larger glyphs, including Chinese, Japanese, and Korean. Noto supports these languages with seven weights.

## Typeface

#### Roboto

Roboto has been refined extensively to work across the wider set of supported platforms. It is slightly wider and rounder, giving it greater clarity and making it more optimistic.

![Examples of Roboto](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7SW9CUzR4MnRpOTg/style_typography_roboto1.png)

![Roboto A-Z and numerals](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7Y3JIMkV5ZmVaM2c/style_typography_roboto2.png)

#### Roboto font weights

Roboto has six weights: Thin, Light, Regular, Medium, Bold, and Black.

![Roboto font weights](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bx4BSt6jniD7ZHlGSHpsMjU5YmM/style_typography_weights1.png)

#### Noto

Noto’s vertical metrics are compatible with Roboto.

![Noto Sans examples for English and CJK (Chinese, Japanese, and Korean)](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzcWkwSW11bkstZEU/style_typography_noto1.png)

![Noto Sans examples for Thai and Hindi (Devangari)](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzOEh3Z1BUNFdsVGc/style_typography_noto2.png)

#### Noto font weights

Noto Sans CJK (Chinese, Japanese, and Korean) has seven weights: Thin, Light, DemiLight, Regular, Medium, Bold, and Black. The weight of Noto Sans CJK Regular is the same as Roboto Regular.

![Noto Sans CJK font weights](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzdFA4NUh2TG1rT1E/style_typography_weight1.png)

Noto fonts for Thai, Devanagari, and all other major living languages have Regular and Bold weights.

![Noto Sans Thai and Hindi (Devangari) font weights](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B_udO5B8pzrzdTRNVG0yX3JkUEE/style_typography_weight2.png)

#### Hinted fonts

Hints are the instructions embedded in a font on how to modify (distort) a glyph to look better on low-resolution displays. As a tradeoff, a hinted font consumes more space than the unhinted version.

Both Roboto and Noto have hinted and unhinted versions. Google recommends:

* Use the unhinted versions on Android and on Mac OS X, which doesn’t implement hints.
* Use hinted fonts on Chrome OS, Windows, and Linux.

#### Font stack

For both Android and web properties, the font stack should specify Roboto, Noto, and then sans-serif.

## Styles

Too many type sizes and styles at once can wreck any layout. A typographic scale has a limited set of type sizes that work well together along with the layout grid.

These sizes and styles were developed to balance content density and reading comfort under typical usage conditions. Type sizes are specified with sp (scaleable pixels) to enable large type modes for accessibility.

#### English and English-like scripts

Latin, Greek, and Cyrillic.

The basic set of styles are based on a typographic scale of 12, 14, 16, 20, and 34.

![](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0Bzhp5Z4wHba3alhXZ2pPWGk3Zjg/style_typography_styles_scale.png)

##### Across form factors, text that appears in the app bar should use the Title style, Medium 20sp

![Examples using title style, English](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsT3hTdEZ3c2JxaUk/style_typography_styles_05_title1.png)

In certain scenarios, use the larger subheading style instead of the smaller Body style. Some of those scenarios include when information is presented as small snippets or when titles are paired with lines of Body-styled text.

![Examples using subheading style, English](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsNVRVTk02WlFCZTg/style_typography_styles_07_subhead1.png)

Button style (Medium 14sp, all caps) is used for all buttons. Button text should be all caps in languages that have capitalization. For languages that don’t have capitals, consider using color text for flat buttons to make them stand out from normal text.

![Examples using Button style, English](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsT3h3cUk3VEp6czQ/style_typography_styles_13_button1.png)

![](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsakpNYVp4YnV6b1U/style_typography_styles_14_button2.png)

## Line Height

To achieve proper readability and appropriate pacing, line heights have been determined based on each style’s individual size and weight. Line wrapping only applies to Body, Subhead, Headline, and the smaller Display styles. All other styles should exist as single lines.

#### English and English-like scripts