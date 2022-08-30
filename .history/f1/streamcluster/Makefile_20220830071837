include ../common.mk

EXE  = streamcluster

.PHONY: run
run:
	./$(EXE) 10 20 256 65536 65536 1000 none output.txt 4

.PHONY: all
all: $(EXE)

.PHONY: clean
clean:
	$(RM) $(EXE)