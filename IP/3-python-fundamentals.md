# 02/05/23 

- Python character set:
	- Letters digits special symbols whitespaces 

> Each word and letter has a token

- Token -> keyword (print, if, elif, etc) 

-  Keywords are predefined, *reserved words* used in Python programming that have **special meanings to the compiler**. 

> Addresses are used to point to a specific value 

- **Variable**: address and value 

Numbers are called integter (int) in a computer.

- Decimals are in two categories: 
  - Float
  - Double 

> Float has a fixed decimal limit but double doesn't.

Procedural languages are C, C++, Java, etc. but **python is a non-procedural language**

- **Procedural language**: It is a type of programming language that uses a linear, step-by-step approach to define and execute instructions. It relies on procedures or functions to organize and control the flow of the program. Eg- C, C++, Rust, Go (Golang).

- **Non-procedural language**: It is a type of programming language that doesn't rely on explicit step-by-step instructions. Instead, it focuses on defining the desired outcome or relationships between data elements, allowing the system to determine how to achieve it. Eg- SQL, HTML, Markdown, Python. 

`int`` is used for numbers only if the user gives an input.  
'char' string is used for just one letter eg. `char a = 'y'`, where a is a variable with the value as the letter 'y'  
'str' is used for a group of letter eg. `str b = "school"`, where b is a variable with the value of the string "school"  

> Note that single quote is used for letters and double quote is used for words but they are the same in python. 

`/` = line separator 

Eg.
```py
# use of separator 
a = "today is/
sunday"
```

> The value of the string is saved in the variable a but printed as separate lines. 

Triple quotes is also used for multiline strings or docstrings. It allows to write multiple lines without the need of separators. 

Eg. 
```py
# use of docstrings
a = '''This is a multiline
string that spans
multiple lines'''

print (a) 
```

08/05/23

- elif: 
	- 'elif' is a keyword used along with 'if' statement to check for additional conditions if the preceding 'if' condition is 'False'. It allows you to specify alternative conditions and code blocks to be executed when those conditions are 'True'. 

Exercise: 

Type B: 

1. 
(a) No error 
(b) Error; variable can't start with number 
(c) No error 
(d) Error; variable can't start with special character
(e) Error; variable can't contain spaces 
(f) Error; float is a keyword 
(g) 


2. 
(i) 1220
(ii) 30
(iii) 2000
(iv) 14.75 

3. 
(i) 'temperature' should be in parentheses 
(ii) Variable "b" not defined and 'And' is invalid syntax 
(iii) Semicolon aren't used for element separator 
(iv) Numbers can't be used as variable 
(v) No separator used 
(vi) "else" is a keyword 

4. 
(i) 13 22 
(ii) 11 3 33
(iii) 7 49 

5. 
(i) print statements couldn't be in codeblocks 
(ii) string can't be added to integer 
(iii) string can't be divided 
