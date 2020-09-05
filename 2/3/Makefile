# ==================
# USING VARIABLES (aka macros)
# ==================
# VARIABLENAME = VALUE OF VARIABLE
# they expand using the syntax $(VARIABLENAME)


TMP = tester1.txt
OUTPUT = tester2.txt

$(OUTPUT): $(TMP)
	cat $(TMP) > $(OUTPUT)

$(TMP):
	echo "this is a test" > $(TMP)
