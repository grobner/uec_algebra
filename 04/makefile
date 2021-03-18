TS=satysfi
GS=dot
GSOPT=-T pdf
HEADERS=lheaders/mystdjareport.satyh mysteamer.satyh listings.satyh matrix.satyh
PRODUCTS=uec-alg4-answer.pdf uec-alg4.pdf roadmap.pdf

.PHONY: clean

all : $(PRODUCTS)

uec-alg4.pdf : uec-alg4.saty $(HEADERS)
	$(TS) uec-alg4.saty

uec-alg4-answer.pdf : uec-alg4-answer.saty $(HEADERS)
	$(TS) uec-alg4-answer.saty

roadmap.pdf : roadmap.dot
	$(GS) $(GSOPT) roadmap.dot -o roadmap.pdf

clean:
	rm $(PRODUCTS)
