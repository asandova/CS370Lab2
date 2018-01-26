all: Lab2.2

Lab2.2: YACC
	gcc y.tab.c -o lab2docalc
YACC: LEX
	yacc -d lab2docalc.y
LEX: lab2docalc.l
	lex lab2docalc.l
