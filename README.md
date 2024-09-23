Har testat med Validator.nu, Jigsaw css och Wave Evaluation tool. 

Validator.nu gav inga error, Jigsaw css gav några error som jag tror kan ha något med hur jag nestade css?
Ändrade nestade cssn och fick inga errors ifrån Jigsaw längre.  

Wave gav contrast error på grund av bilden så jag gjorde "overlayen" som dimmade bilden lite mörkare och lade till en liten bakgrund till h1an specifikt också och då fixades det.


Blev lite scaling problem med bilden på mindre skärmar så jag ändrade bildens storlek litegrann och lade till en media query för hero texten

När jag gör en hård inläsning och tömmer cachen med no throttling så tar det ~50-70ms, jag hade en gång som det tog mycket längre (~500ms) men kan inte replikera det. 
