Wed 02 Sep 2020 11:27:39 BST

# bash/functions
note 

When using the curly braces {} notation, make sure to separate the content of the function and the braces with blanks or newlines, otherwise, a syntax error near unexpected token will be raised. This is due to historical reasons as the braces are reserved words and can only be recognized as such when they are separated from the command list by whitespace or another shell metacharacter. Also when using the braces notation, you must terminate the last command by a semi-colon ;, an ampersand &, or a newline.

___
[bash functions](https://www.shell-tips.com/bash/functions/)
[home](./home.md) 
[index](./index-file.md)
