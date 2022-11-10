# How to use?

[Sample apk](https://github.com/Shlyankin/tesseract-ocr-android-sample/blob/6cff71f93de7a1d49586836bb2fd8d7d7b332b80/app-release.apk)

1) Focus image by click on the preview view
2) Click "OCR" button
3) Wait dialog window (about 5-10 sec)

Also you can enable "show text bounds" options in toolbar menu

# Fork Info

Changes:
- Changed Tesseract Android library: cz.adaptech.tesseract4android:tesseract4android:4.1.1a
- Created simple jks for test release build
- Updated gradle plugin, wrapper
- Added androidx
- Added rus symbols

tesseract4android:4.1.1a contains:
- Tesseract OCR 5.0.1
- Leptonica 1.82.0
- libjpeg v9d
- libpng 1.6.37

# tesseract-ocr-android-sample

Simple android application for text recognition. Application uses tess-two library (android wrapper for tesseract-ocr) for performing text recognition tasks.

Application abilities:
- determination of recognized text regions directly from frames captured by smartphone camera
- displaying recognized text regions over the frames captured by smartphone camera at real time
- performing text recognition of frames captured by smartphone camera
