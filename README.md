# པར་གཞི་སྒྲིག་ཆས། Pecha Printer
Program to convert a pdf into a ready to print "Pecha", traditional Tibetan volumes.

### ཕབ་ལེན། Download Installer

* [སྒེའུ་ཁུང་རྟགས་ཅན། Windows](https://github.com/buda-base/pecha-printer/releases/download/v1.3/PechaPrinter_1.3.exe)

## ཚད་མཐོའི་འཇུག་སྤྲོད། Advanced Install
* ཀུ་ཤུ་རྟགས་ཅན་ཆེད། Mac & Linux:
    1. [ཕེ་ཐོན་མ་ལག་ཐོན་རིམ་ 3.7 ཕབ་ལེན་བྱས་ཏེ་འཇུག་སྤྲོད་བྱོས། Install Python 3.7](https://www.saintlad.com/install-python-3-on-mac/)
    2. [པར་གཞི་སྒྲིག་ཆས་ཀྱི་ཁུག་མ་ཕབ་ལེན་བྱོས། Download Pecha Printer](https://github.com/buda-base/pecha-printer/archive/master.zip)
    3. Open Terminal and run `python3 install.py`
    4. Open Terminal and run `python3 pechaprinter.pyw`

## Logic for a pecha with 15 images
- printing one pecha page per paper sheet is wasteful
- grouping images 3 by 3 in photoshop is difficult and time consuming
![pecha-printer logic (6)](https://user-images.githubusercontent.com/17675331/133664359-c56566b7-1ff1-4582-9f4a-0a399025c9b0.png)
- order A adds a lot of reordering work after cutting the printed pecha
- order B only requires to combine the 3 piles to get a pecha ready for reading!
![pecha-printer logic (2)](https://user-images.githubusercontent.com/17675331/133428067-3aaac826-5648-4d14-aecf-aad475032795.png)
![](https://user-images.githubusercontent.com/17675331/133585088-abee06b0-aa65-4e5d-9073-14fb037d9690.png)

## Development Roadmap
### To do:
- [x] Windows installer
- [ ] Mac installer
- [x] redesign the UI
- [x] localization
- [ ] custom paper size
- [ ] option to binarise all images for unity
- [ ] combine multiple pdfs
- [x] bundle for distribution

### Wish list:
- split pdfs on outline and name files after section names

## License

The code is Copyright 2019 Buddhist Digital Resource Center, and is provided under [Apache License 2.0](LICENSE).
