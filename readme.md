# Fabricator Typography Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.typography --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.typography.les`.

## Usage

Variables available in this file you can override:

```
@linkOutline: 'no-change';
@linkColor: blue;
@linkDecoration: underline;
@linkColorHover: darken(@linkColor, 10%);
@linkDecorationHover: @linkDecoration;
@linkColorActive: darken(@linkColor, 20%);

@headingColor: #000;
@headingFont: Tahoma, Geneva, sans-serif;
@headingFontWeight: bold;
@headingLineHeight: 1.4em;
@headingMarginBottom: 20px;

@headingLevel1FontSize: 36px;
@headingLevel2FontSize: 32px;
@headingLevel3FontSize: 28px;
@headingLevel4FontSize: 24px;
@headingLevel5FontSize: 20px;
@headingLevel6FontSize: 16px;

@paragraphColor: lighten(#000, 25%);
@paragraphFontWeight: normal;
@paragraphLineHeight: 1.3em;
@paragraphMarginBottom: 20px;

@smallFontSize: .8em;

@quoteColor: @paragraphColor;
@quoteFont: Georgia, Times, serif;
@quoteFontSize: false;
@quoteFontWeight: normal;
@quoteLineHeight: @paragraphLineHeight;
@quoteFontStyle: normal;
@quotePaddingHorizontal: 2em;
@quotePaddingVertical: 1em;
@quoteMarginBottom: @paragraphMarginBottom;
@quoteBorderLeft: false;
@quoteBorderLeftColor: @quoteColor;

@citeColor: lighten(#000, 65%);
@citeFont: @quoteFont;
@citeFontSize: false;
@citeFontWeight: @quoteFontWeight;
@citeLineHeight: @quoteLineHeight;
@citeFontStyle: @quoteFontStyle;
@citeMarginTop: 14px;
@citeIndicator: '\2014\00a0';
```
