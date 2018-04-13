# favicons #

These are templates and sample favicons for websites.

There are three types of favicons a site can have:

* the legacy 16×16 Microsoft Windows icon that is compatible with every known browser that uses favicons at all
* the newer transparent PNG images used by modern broswers and mobile devices.
* application icons used by devices like the iPhone for making an application shortcut for a website

## Legacy Icons ##

Here, we currently have a template and sample 16×16 Microsoft Windows icon. You
can edit the Gimp image file `16x16.xcf` to create your own.

When you're finished editing, in Gimp, choose "File -> Export...". Make the
filename `favicon.ico`. In the dropdown at the bottom for type, choose
"Microsoft Windows icon (*.ico)". Click "Export". It will bring up an options
dialog. The defaults should work.

We have a sample blank favicon in `samples/blank.ico`. This is a good default
icon to use if you don't want browsers requesting this file over and over
again, filling up your server logs. Rename if `favicon.ico` and make it
available at the root of your site's domain, ie.
`http://example.com/favicon.ico`.
