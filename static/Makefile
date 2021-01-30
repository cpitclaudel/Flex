default: stylesheet/style.min.css

stylesheet/%.min.css stylesheet/%.map: stylesheet/%.less
	lessc --clean-css $< $@
