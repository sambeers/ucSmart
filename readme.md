ucSmart
=======

A more efficent version of the native ucwords function in php. In fuction.php you can see it looks for smaller words that you wouldn't normally want to have capitized automatically. You can edit this list or add entries that you specifically always want lowercase.

~~~~include_once"function.php";~~~~
~~~~echo ucSmart($string);~~~~

Invoke the function above to capitalize a phrase but avoid having articles and conjuctions grouped in there. Best used for titles on a website. Using this makes the site/app look more professional because it's free of human error.

Future Things
-------------

Ideally this will grow to something i can just wrap around any line of text i want to echo and have it figure out how to properly format it. With an additional value passed in to know whether to treat it as a title or body text.

I'm currently working on a way to add a list of words that should always be capitalized in a specific way too. Like the obligitory "jQuery" that this otherwise would write Jquery. These words should be accessable through an array and be easily modified by the developer.
