# page-builder-css-styles
Example css rules to style your page-builder pages

You can add styles via each text or form block's style button (it looks like an artist's pallette), but if you want more control and to apply styles to your template so they always apply it is recommended you use CSS.

CSS can be added directly into your template's header, between the <head> and </head> tags. For example this would style text that is marked as Heading 1:

<style>h1 {margin: 1.7rem 0; font-size: 3rem; font-weight: bold;}</style>

Alternatively you can add your styles to an "external stylesheet". You can create these in Notepad and save them as a file ending in .css. Then upload them to your library and "call" them in your template, for example:

<link rel="stylesheet" type="text/css" href="https://aaf1a18515da0e792f78-c27fdabe952dfc357fe25ebf5c8897ee.ssl.cf5.rackcdn.com/1757/example-stylesheet.css?v=1516627625000" />

