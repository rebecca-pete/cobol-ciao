# COBOL-Ciao

This repo includes several exercises illustrating simple COBOL programs.

## Setup

The following instructions are optimized for a Mac user running VS Code.<br/>

When opening in VS Code for the first time, install the COBOL Source colouriser extension for easier viewing.<br/>

1. Clone this repo to your local machine.<br/>

1. `cd` into the cloned repo folder.<br/>

1. From the CLI, run `brew install open-cobol`.<br/>

### Exercise: 1

The following program shows you how to print the string, "Ciao!" using COBOL.

1. The "Ciao!" text can be found in the `test.cbl` file. `cd` into the folder where this file is located.<br/>

    To compile the `test.cbl` file into an executable binary, run `cobc -free -x -o test test.cbl`.<br/>

    The `-free` flag tells GnuCOBOL to be more lenient when parsing code (rather than requiring extremely precise formatting), and the `-x` flag tells GnuCOBOL to generate an executable file.<br/>

2. Run `ls`. As you can see, you have a binary executable file called `test` that you can execute. To do so, run `./test`.

    *Note:* If you cloned this repo, the executable files should already be included. I am adding this step to illustrate how to create an executable in COBOL if you wish to create a new program.

3. You should now see the text, `Ciao!` printed in your CLI.

### Exercise: 2

The following program shows you how to multiply two single-digit inputs using COBOL.

1. From the CLI, run `cobc -free -x multiply.cbl `.<br/>

1. The code with the multiply logic is located in the file `multiply.cbl`. As in the previous exercise, compile `multiply.cbl` into an executabe binary file. To do so, run `cobc -free -x multiply.cbl `.<br/>

1. To run the executable you just created, run `./multiply` in the CLI.<br/>

1. When prompted, enter any one-digit number. For this example, `3`.<br/>

1. When prompted, enter a second one-digit number. For this example, `7`.<br/>

1. You should see the following output: `Result is = 21`

**Sources:**<br/>
[Linux Magazine Tutorial - COBOL](https://www.linux-magazine.com/Issues/2017/204/Tutorials-COBOL#article_l2)<br/>
[WTF is COBOL?](https://youtu.be/TKOr43VmlC0)<br/>
[GnuCOBOL Guides](https://open-cobol.sourceforge.io/)<br/>
[GnuCOBOL Forum](https://sourceforge.net/p/open-cobol/discussion/help/thread/99697726c5/)<br/>
