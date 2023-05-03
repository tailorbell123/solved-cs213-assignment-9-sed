Download Link: https://assignmentchef.com/product/solved-cs213-assignment-9-sed
<br>
<span class="kksr-muted">Rate this product</span>

<ol>

 <li>script1.sh:Write a sed command/script to emulate wc -l command. This file is run as a bash script by typing : . script1.sh filename.txt</li>

 <li>script2.sedWrite a sed script which takes an input file and puts a line number at the beginning of each line.This file is run as a bash script by typing : . script2.sh filename.txt For example :input.txt has the following contents:this is first linethis is third line this is fourth line.1</li>

</ol>

should be written to output.txt as follows: See that all blank lines also get a number.(1) this is first line

(2)(3) this is third line

(4)

this is fourth line

3. script3.sed:Given input files contains new-lines and white spaces and tabs. Write a sed script to

<ol>

 <li>(a)  Remove all leading spaces</li>

 <li>(b)  Collapse every sequence of white spaces between two words in a single line into a single space, and</li>

 <li>(c)  Collapse every sequence of white spaces between two lines into a single newline. All other suffix and prefix whitespaces are to be deleted.</li>

 <li>(d)  Print the output to screen. For example</li>

</ol>

” how are you

fine.

”

becomes

” how are you fine.”

4. script4.sed :There is a text file called input.txt such that there are four “strings” on each line.

For example:

VeenaDaniel Raj 3456 Veena Michael Raj3456

2

This has to be written so that all four fields in the record (line) are sepa- rated by a single tab. Therefore above output looks like