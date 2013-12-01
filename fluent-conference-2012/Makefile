minify:
	@cat  c/style-*.css | java -jar external/yuicompressor-2.4.6.jar --type css > c/min.css
	@echo "Gerado css min"
	@cat j/app-*.js | java -jar external/yuicompressor-2.4.6.jar --type js > j/min.js
	@cat j/prettify.js | java -jar external/yuicompressor-2.4.6.jar --type js > j/prettify-min.js
	@echo "Gerado js min"