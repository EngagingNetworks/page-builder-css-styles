In some circumstances, a target block's HTML message (but not plain text or editable areas) might appear to run outside of its container.

This can happen if you have  this in your template:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

And if the page is viewed in the Safari browser on mobile iOS. 

This style can fix this issue by giving the target block's HTML message a width:

```css
@media only screen and (min-device-width : 375px) and (max-device-width : 667px) {
.pb .en__contactMessage__htmlDisplay iframe {
width: 300px;
}
```
