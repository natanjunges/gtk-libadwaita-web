.PHONY: all clean

all: Default-light.css Default-dark.css Default-hc.css Default-hc-dark.css

Default-%.css: Default-%.scss _colors-public.scss _colors.scss _common.scss _drawing.scss
	sassc -a -M -t compact $< $@

clean:
	rm -f Default-light.css Default-dark.css Default-hc.css Default-hc-dark.css
