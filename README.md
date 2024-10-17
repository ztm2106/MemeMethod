# MemeMethod
Teammates:
Name: Zakiy Manigo UNI: ztm2106
Name: Roshan Prakash UNI: rp3187

Output of sample input from first draft of code:
('KEYWORD', 'create')
('KEYWORD', 'meme')
('KEYWORD', 'background')
('ID', 'blue')
('KEYWORD', 'load')
('ID', 'pictures')
('ID', 'dogs')
('ID', 'cats')
('ID', 'grass')
('KEYWORD', 'size')
('INT', '1024')
('ID', 'x')
('INT', '1024')
('KEYWORD', 'border')
('ID', 'solid')
('ID', 'color')
('KEYWORD', 'style')
('ID', 'collage')
('KEYWORD', 'text')
('STRING', 'we all love animals')
('KEYWORD', 'placement')
('ID', 'middle')
('KEYWORD', 'overlay')
('ID', 'yes')
('KEYWORD', 'text')
('STRING', 'of course')
('KEYWORD', 'placement')
('ID', 'bottom')
('KEYWORD', 'overlay')
('ID', 'no')
('KEYWORD', 'count')
('INT', '50')
('KEYWORD', 'save')
('KEYWORD', 'images')

-- x should be an OP not an ID

Output of sample input from the second draft of code:
('KEYWORD', 'create')
('KEYWORD', 'meme')
('KEYWORD', 'background')
('ID', 'blue')
('KEYWORD', 'load')
('ID', 'pictures')
('ID', 'dogs')
('ID', 'cats')
('ID', 'grass')
('KEYWORD', 'size')
('INT', '1024')
('OP', 'x')
('INT', '1024')
('KEYWORD', 'border')
('ID', 'solid')
('ID', 'color')
('KEYWORD', 'style')
('ID', 'collage')
('KEYWORD', 'text')
('STRING', 'we all love animals')
('KEYWORD', 'placement')
('ID', 'middle')
('KEYWORD', 'overlay')
('ID', 'yes')
('KEYWORD', 'text')
('STRING', 'of course')
('KEYWORD', 'placement')
('ID', 'bottom')
('KEYWORD', 'overlay')
('ID', 'no')
('KEYWORD', 'count')
('INT', '50')
('KEYWORD', 'save')
('KEYWORD', 'images')

-- code seems correct. we are getting 5 different token types that are parsed correctly.

Token Types seen:
KEYWORD: Represents keywords in the language like create, meme, background, load, etc.

ID: Represents identifiers, which include words like blue, dogs, solid, etc.

INT: Represents integer literals like 1024, 50.

STRING: Represents string literals like "we all love animals", "of course".

OP: Represents operators, in this case, just x.

Running Everything:

make program an executable: chmod +x run_meme_lexer.sh

this is how to run the lexer with shell script:
./run_meme_lexer.sh