ucSmart
=======

A more efficent version of the native ucwords function in php. Instead of capitalizing each string, it uses title-case, ignoring smaller 
articles and conjunctions. In fuction.php you can see it looks for these words in a blacklist array. You can edit this list or add 
additional entries that you specifically always want lowercase. I have found automating capitalization to be very helpful in my own work, it 
really keeps things looking professional having your titles free of human error.


Usage
-----

```
include_once"function.php";
echo ucSmart($string);
```
Include the script or paste the contents into your working file. Then invoke the "ucSmart" function to capitalize a phrase in title-case.


Future Things
-------------

Eventually I'd like to grow this into something I can just wrap around any line of text and have it figure out how to properly 
format it. Meaning that I'd like to be able to use this same automation for body-text as well. Something like capitalize the first word in a
sentence as well as matches to a proper-nouns whitelist?

I'm currently working on a way to add a list of words that should always be capitalized in a specific/unusual way too. Like the obligitory 
"jQuery" that this otherwise would write Jquery. Or your company name that's spelled like: CompanyName. These kinds of words should be accessable 
through annother array and could be easily redefined by the developer.


Donate
------

If you found this project usefull please consider sending a couple bucks my way as a thank you for the work :)

[PayPal](https://paypal.me/sammurphey) · [Venmo](https://venmo.com/sammurphey) · [KoFi](https://kofi.com/sammurphey)

