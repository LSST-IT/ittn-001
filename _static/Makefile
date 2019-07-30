TEMPFILE := $(shell mktemp -u)

all: foreman_smee.png

%.png : %.dot
	dot -Tpng $< -o $@

clean:
	rm *.png
