NAME = dossier
COMP = pdflatex 
BIN= ../bin/

all:
	$(COMP) $(NAME).tex

#compiler deux fois pour mettre à jour la table des matières
twice: 
	$(COMP) $(NAME).tex
	$(COMP) $(NAME).tex

clean: 
	rm -f $(NAME).aux $(NAME).log $(NAME).out $(NAME).toc
