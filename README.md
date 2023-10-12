# Te.Comp.Helper
Dieses Skript automatisiert den Tipptrainer in Te.Comp

# INSTALLATION
Diese Installation ist sehr sehr aufwendig. Benutzung auf eigene Gefahr!

## Installiere Python 3.11.6 (Diese Version nutze ich) 
Nimm alle extras, PATH, etc. https://www.python.org/ftp/python/3.11.6/python-3.11.6-amd64.exe

## Installiere PIP
In CMD: "curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py"\
Danach auch in CMD: "python C:\Users\User\Downloads\get-pip.py" _Deinen Pfad einfügen_

## Installiere folgende PIPs mit diesem CMD-Befehl in CMD
pip install pytesseract pywinauto pillow psutil pyautogui pynput

## Installiere Tesseract OCR
https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-5.3.3.20231005.exe

## Setze den richtigen Pfad zu Tesseract OCR in "te.comp.py"
### Mein Pfad:
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'

## Ändere den Source-Code von PyAutoGui
### Mein Pfad:
C:\Users\Schule\AppData\Local\Programs\Python\Python311\Lib\site-packages\pyautogui\
<p>Von dort löscht du die '__init__.py' Datei und fügst die aus dem Ordner "PyAutoGuiCustom" ein

# BENUTZUNG
Öffne "te.comp-training starten". Gehe in einen Tipptrainer. Starte die Python-Datei, dass Schreiben erfolgt Automatisch!

# WICHTIG!
Umlaute wie Ö, Ä, Ü, ö, ä, ü, aber auch Hochzahlen wie ² und ³ müssen selber geschrieben werden. Wenn eine erscheint wartet das Skript 5 Sekunden, in der Zeit fügst du den Buchstaben oder die Hochzahl ein und wartest wieder bis es weiterschreibt.

![Te Comp Tipptrainer](https://github.com/OVRBCK/Te.Comp.Helper/assets/110503465/6b0d323b-b1a4-4c12-ab42-1c18f9a2498a)

# INFORMATIONEN
Die Geschwindigkeit liegt bei 2700 Anschlägen die Minute im Durchschnitt.
