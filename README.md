# vv-wrangle
To work  more on git bash and powershell commands

[Play](http://shakespeare.mit.edu/julius_caesar/full.html)

Speaker 1: TITINIUS

Speaker 2: MESSALA

Question Asked : To count the number of times speaker1 and speaker2 are repeated in the play

curl command : curl "http://shakespeare.mit.edu/julius_caesar/full.html" -O "input.txt

$ grep -i 'MESSALA' input.txt -c

To get the count of MESSALA  in the file.

$ grep -i 'TITINIUS' input.txt -c

To get the count of TITINIUS in the file

$ messala=$(grep -i 'MESSALA' input.txt -c)
To assign the count of messala to variable messala

$ titinius=$(grep -i 'TITINIUS' input.txt -c)
To assign the count of titinius to variable titinius

$c=$((messala+titinius))
To add the count of both words.

$ echo $c
To display the total count

echo $c > Totalcount.txt
To redirect the output to file Totalcount.txt

The total count of the words MESSALA and TITINIUS is 82

























[Reference to add two variables](https://unix.stackexchange.com/questions/250204/how-to-add-two-variables-passed-in-the-shell-which-returns-integer-count)
