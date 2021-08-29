# Makefile
TARGETS: index.html
.PHONY: all clean

all: $(TARGETS)

clean:
	$(RM) $(TARGETS)

%.html : %.md
	pandoc -s $< -o $@
