# Wikipedia_search
 ########a function wikipage2file(wikipedia_pagetitle, output_filepath),
which takes as input two arguments: a string for the title of a Wikipedia page and a string
representing an output folder where the output will be saved. The function performs the
following operations.
(1) Searches all Wikipedia pages that can be retrieved with the wikipedia_pagetitle
string.
(2) Retrieves the first candidate Wikipedia page and obtains two strings: the title and
the content of that page.
(3) Writes a text file named wikipage.txt, where wikipage should be replaced by the
Wikipedia page's title (but remove spaces in the filename). The resulting page should
have, in the first line, the title, then two blank lines, and then the content of the
page.
##########a function similar(x,y) that returns a float number based on the following:
Given two Wikipedia pages x and y, it calculates how similar they are based on the following
operations:
(1) Compute the set containing every word that occurs in x at least once. Do the same
for y.
(2) Obtain the set of the words that are contained both in x and in y.
(3) Obtain the set of all the words contained in x or y (including words contained in both
x and y).
(4) Return the result of dividing the length of the set in (2) by the length of the set in (3).
The function should always return a value between 0 and 1 (with 0 being no
similarity).
