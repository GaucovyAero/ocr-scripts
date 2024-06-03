# ocr-scripts
My OCR scripts that I use for grabbing text from images with tesseract. 

Written in Bash. Using them requires a screenshooter (uses `scrot` by default), `xclip` and `tesseract`

`ocr-image` takes 1 argument - the language used by tesseract. It is always 3 letters long and can be found via your package manager, e. g. `eng` for English
`ocr-file` takes 2 arguments - the language and the file path.
