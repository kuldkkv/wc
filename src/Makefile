
DISTDIR=../dist
EXE=$(DISTDIR)/mywc

EXE: lex.yy.c
	cc lex.yy.c -lfl -o $(EXE)

lex.yy.c: wc.l
	lex wc.l
