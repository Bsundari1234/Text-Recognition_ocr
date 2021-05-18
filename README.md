# Text-Recognition_ocr
Hello, this is a mini project where i implemented text recognition using easy OCR method
import easyocr
reader = easyocr.Reader(['ch_sim','en']) # need to run only once to load model into memory
result = reader.readtext('chinese.jpg')
