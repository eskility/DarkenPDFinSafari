Tired of hurting your eyes with white PDFs?

Just enable the [developer tools in safari](https://support.apple.com/en-az/guide/safari/sfri20948/mac) and paste the following command in the javascript console(Option + ⌘ + C.)

document.embeds[0].style.filter = 'grayscale(100%) invert(100%) sepia(100%) contrast(75%)';

Adjust to your preference.


You can also make the background fit perfectly to the dark background of the Notes app. This makes your screenshots of the PDF fit perfectly.
document.embeds[0].style.filter = 'grayscale(100%) invert(100%) sepia(100%) contrast(76.3%)';

