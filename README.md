# poster template

Written by Tom Frömbgen for the Kirchner group at the University of Bonn.

## Usage

This is our template for scientific conference posters. Feel free to adjust it to your needs, but please keep the overall design. Please do not modify this repository directly.

See the [example poster](main.pdf) for a preview.

There are two main files of interest:
* [`main.tex`](main.tex) contains the actual poster content
* [`preamble.tex`](preamble.tex) contains the preamble and the style definitions

I have planned on two main adjustments that might be relevant for you:
1. The header of the poster. In the current example, a secondary logo is present. If you do not have one, you can comment the corresponding lines in [`preamble.tex`](preamble.tex) and uncomment the lines for an additional grey bar around the title.
2. The block color. The default color is Uni Bonn gray. In case you want to adjust the color of a block, you can do so by adjusting the `\usecolorstyle` command in [`main.tex`](main.tex). Take a look at the file for a description.

Have fun.
