# ==================
# USING COMMAND VARIABLES
# ==================
# for the depence variable = VALUE OF VARIABLE

TMP = tester.txt
TMP2 = tester1.txt
DEPS = $(TMP) $(TMP2)
OUTPUT = tester2.txt

$(OUTPUT): $(DEPS)
	cat $(DEPS) > $(OUTPUT)

$(TMP):
	echo "this is a test" > $(TMP)

$(TMP2):
	echo "this is a test2" > $(TMP2)
