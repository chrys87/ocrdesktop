# ocrdesktop
Accessiblity tool for use the current window with OCR technique 

# Here is the wiki:
https://wiki.archlinux.org/index.php/Ocrdesktop

# Depencys:
- python3
- tesseract
- tesseract-lang-<yourLanguageCode>
- python3-pillow
- python-atspi
- python-pytesseract
- libwnck3
- GTK3
# Optional Depencys
- python-scipy (for color detection)
- python-webcolors (for color detection)
- python-pdf2image (for pdf support)

# INSTALL

## ARCH Linux stable
$ pacman -S ocrdesktop

## ARCH Linux git 
$ yay -S ocrdesktop-git

## Just the Depencys:
$ yay -S python tesseract tesseract-data-deu tesseract-data-eng python-pillow python-atspi libwnck3 gtk3 python-webcolors python-scipy python-pytesseract python-pdf2image



