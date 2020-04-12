# COBOL-Ciao

The following is a simple "Hello world!" or "Ciao!" program using COBOL.

## How to use this program

 *Note:* The following instructions are optimized for a Mac user running VS Code.

1. Clone this repo to your local machine.

1. From the CLI, run `brew install open-cobol`.
 *Note:* When opening in VS Code for the first time, install the COBOL Source colouriser extension for easier viewing.
1. The "Ciao!" text for printing can be found in the `test.cbl` file. `cd` into the folder where this file exists. To compile the `test.cbl` file into an executable binary, run `cobc -free -x -o test test.cbl`.
1. The `-free` flag tells GnuCOBOL to be more lenient when parsing code (rather than requiring extremely precise formatting), and the `-x` flag tells GnuCOBOL to generate an executable file. Afterward, you have a binary called `test` that you can execute. To do so, run `./test`.
1. You should see the text, `Ciao!` from your CLI.

**Sources:**<br/>
[Linux Magazine Tutorial - COBOL](https://www.linux-magazine.com/Issues/2017/204/Tutorials-COBOL#article_l2)<br/>
[WTF is COBOL?](https://youtu.be/TKOr43VmlC0)<br/>