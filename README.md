# MLOps & Cloud DB Website

Source code for https://mlops-and-cloud-db.com

## Convert Images

SVG to favicon.ico
```bash
$ convert -background transparent -define 'icon:auto-resize=16,24,32,64' logo.svg favicon.ico
```

Color to Grey
```bash
$ convert source.jpg -colorspace Gray destination.jpg (true grayscale only)
$ convert source.jpg -monochrome destination.jpg (true black and white)
$ convert source.jpg -separate destination.jpg (separate into gray channels)
```
