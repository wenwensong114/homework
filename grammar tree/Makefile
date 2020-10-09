all:
	bison -d grammar/cal.y
	flex grammar/cal.l
	gcc grammar/cal.tab.c grammar/lex.yy.c -lfl -ly
	./a.out
	dot tree/tree.dot -Tpng -o tree.png
