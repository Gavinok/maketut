# ==================
# ACTIONS AS TARCETS
# ==================

.SUFFIXES: .tmp .txt

all: tester.txt

# make a .txt file using a .tmp file
# $< for the .tmp file
# $@ for the .txt file

# .inextension.outextension:
.tmp.txt:
	cat $< > $@

# Now we can run `make clean` and remove all text files
clean:
	rm *.txt
