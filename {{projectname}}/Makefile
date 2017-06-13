{{projectname}}.pdf: {{projectname}}.dvi
	dvipdf {{projectname}}.dvi

{{projectname}}.dvi: {{projectname}}.ltx
	latex {{projectname}}.ltx

.PHONY: clean
clean:
	rm {{projectname}}.dvi {{projectname}}.log {{projectname}}.aux {{projectname}}.pdf
