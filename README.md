# operator_overload_c
Overloaded operators for a basic calculator.

• Makefile
– This is the file that is used to build the project. You can build the project by just typing make on the command line.<br />
• calc.l<br /><br />
– This file contains the lex specification for the calculator project.<br />
• calc.y<br /><br />
– This file contains the yacc specification for the calculator project.<br />
• input.txt<br /><br />
– This file contains list of mathematical function that you are going to test your calculator.



USAGE

1.	First you should install these programs: gcc, make, flex, bison. (flex is a lexical analysis tool, bison is a kind of yacc tool for parser generator). For installation, you can use the following command in Ubuntu:
sudo apt-get install gcc make flex bison

2. Go into project folder and run make command. make will compile your source codes according to the rules in Makefile.
make

3. to test your program:
Make test file=input1.txt
