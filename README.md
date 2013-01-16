News Manager Title
==================

Easily replace/update GetSimple pages' title tag with News Manager post titles.

Requires:
 - GetSimple CMS 3.0+
 - News Manager plugin 2.2.4+

Usage:    
install (upload to plugins folder) and activate

Customization:    
You can edit the following settings in the plugin file, or better insert them to your site's *gsconfig.php* file

```
# Insert post title into/instead of page title. 1 = before, 2 = after, 0 = replace. Default 1.
define("NMTPOSITION",1);

# Text to be used as separator between page title and post title. Default " - "
define("NMTSEPARATOR"," - ");
```
