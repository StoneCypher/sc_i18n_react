sc_i18n_react
=============

Simple internationalization controls for [react.js](http://facebook.github.io/react/); largely 
a wrapper of [sc_i18n](https://github.com/StoneCypher/sc_i18n).  MIT licensed.





What's going on here
--------------------

Internationalization is surprisingly difficult, and Javascript isn't exactly helping.  This
library exists in the hope of easing the process of developing international applications under
the `react.js` UI library.

Consider a few examples of how various cultures write the number one million point four:

| Who         | With    | How         |
|-------------|---------|-------------|
| Murica      | English | 1,000,000.4 |
| Britain     | English | 1,000,000·4 |
| Canada      | Eng/Fr  | 1 000 000.4 |
| France      | French  | 1 000 000,4 |
| Germany     | German  | 1.000.000,4 |
| Switzerland | Swiss   | 1'000'000.4 |
| India       | Hindi   | 10,00,000.4 |
| China       | English | 100,0000.4  |

Now, the want to write &lt;iNumber value="1000000.4"/&gt; might be obvious. `:)`