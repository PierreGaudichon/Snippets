### Compress pictures

```bash
convert -resize 1280x1280 -quality 75 <image_source>.bmp <image_destination>.jpg
```

### Browserify

```bash
browserify \
	-x lodash \
	-t browserify-data \
	-t coffeeify \
		--extension=".coffee" \
	-t browserify-global-shim \
		--lodash="_" \
	src/index.coffee > public/app.js
```

### Thepiratebay

```bash
echo "104.28.4.42     thepiratebay.se" >> /etc/hosts
```
