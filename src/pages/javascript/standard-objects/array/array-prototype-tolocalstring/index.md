---
title: Array.prototype.tolocalstring
---
## Array.prototype.tolocalstring
<h3>SYNTAX</h3>

                          yourArray.toLocaleString();
                          yourArray.toLocaleString(locales);
                          yourArray.toLocaleString(locales, options);


<i>This method changes your <b>Array</b> into a <b>string</b></i>. If your array contains numbers, the method automatically adds commas.

For Example:
```javascript
var productCost = [3,10,20,30,40,9000,1000000];

var makeMeIntoAString = productCost.toLocaleString();

// returns      "3,10,20,30,40,9,000,1,000,000"
```
```javascript
var adjectives = ["alluring", "bizarre", "fascinating", "weird"];

var stringMe = adjectives.toLocaleString();


// returns      "alluring,bizarre,fascinating,weird"
```
<h3>Optional Parameters</h3>

<h5>Locales</h5>

You are able to pass a locale parameter into this method. You can use either one <a href='https://tools.ietf.org/html/rfc5646#appendix-A' target='_blank' rel='nofollow'>BCP 47 language tag </a>or as many BCP 47 language tags as you want (formatted in an array).

<h5>Options</h5>

This parameter has to be formatted as an object, and allows you to configure the string output. It is very helpful with <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toLocaleString' target='_blank' rel='nofollow'>dates</a> and <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/toLocaleString' target='_blank' rel='nofollow'>numbers</a> that you may want to standardize.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

Please Note: Not all browsers support locales and options arguments. Check for compatibility.
#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
<a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/toLocaleString' target='_blank' rel='nofollow'>MDN Array.prototype.toLocaleString()</a>
<h4>Further Information About Locales</h4>
<a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl' target='_blank' rel='nofollow'>MDN Locales Argument</a></br>
<a href='http://www.rfc-editor.org/rfc/rfc5646.txt' target='_blank' rel='nofollow'>BCP 47 Language Tags</a>
