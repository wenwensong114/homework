all:
	bison -vdty src/calc.y
	flex src/calc.l
	gcc -o calc y.tab.c lex.yy.c
	./calc
        
