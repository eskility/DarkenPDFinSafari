# DarkenPDFinSafari
Tired of hurting your eyes with white PDFs?

Just enable the [developer tools in safari](https://support.apple.com/en-az/guide/safari/sfri20948/mac) and paste the following command in the console.

document.embeds[0].style.filter = 'grayscale(100%) invert(100%) sepia(100%) contrast(75%)';

Adjust to your preference.
