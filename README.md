# page-builder: CSS styles

You can styles text and form block by clicking their tyle button (it looks like an artist's palette), but if you want more flexibility and to apply styles to your template so they apply automatically to every page, it is recommended you use CSS.

## How to use these example styles

**The rules in this repository assume you have added a class "pb" to your body tag to help override any existing stylesheets.** You can do this like this:

```html
<body class="pb">
  ```

CSS can be added directly into your template's header, between the ```<head>``` and ```</head>``` tags. For example this would style text that is marked as Heading 1:

```html
<style>
h1 {
  margin: 1.7rem 0;
  font-size: 3rem;
  font-weight: bold;
}
</style>
```

Alternatively you can add your styles to an "external stylesheet". You can create these in Notepad and save them as a file ending in .css. Then upload them to your library and link to them in your template, for example:

```html
<link rel="stylesheet" type="text/css" href="https://aaf1a18515da0e792f78-c27fdabe952dfc357fe25ebf5c8897ee.ssl.cf5.rackcdn.com/1757/example-stylesheet.css?v=1516627625000" />
```

## What examples are there?

### Column styles
Columns have the same height by default - use this to change that https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/columns-unequal-height.css

Column gaps for two-column rows https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/two-column-row-column-gap.css

### Field styles
Add a asterisk to the label if mandatory https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/fields-mandatory-asterisk.css

Fancy checkboxes, instead of default https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/fields-checkbox-fancy.css

Fancy donation buttons, to choose the amount https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/fields-donation-amount-radio-fancy.css

Show a currency symbol inside the Other donation box https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/fields-show-currency-symbol-inside-other-donation-input.html

### Email to target - Target block styles
HTML message fix, if running outside of box https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/target-block-html-message-displaying-wrong.md

### EVents - Ticket block styles
Hide the additional donation box https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/events-hide-additional-donation-block.html

### Social sharing styles
Change the icons that appear for Twitter and Facebook: https://github.com/EngagingNetworks/page-builder-css-styles/blob/master/change-social-share-simple-icons.css

