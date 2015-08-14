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
- python-tesserwrap >=0.1.6 (https://pypi.python.org/pypi/tesserwrap)
- libwnck3
- GTK3

# INSTALL 
ARCH Linux

$ pacman -S python tesseract tesseract-data-deu tesseract-data-eng python-pillow python-atspi libwnck3 gtk3

$ yaourt python-tesserwrap

Run "ocrdestkop"

OR the offical package in the AUR

$ yaourt ocrdesktop
