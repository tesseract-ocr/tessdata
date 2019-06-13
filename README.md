tessdata
========

These language data files only work with Tesseract 4.0.0.
They are based on the sources in
[tesseract-ocr/langdata](https://github.com/tesseract-ocr/langdata) on GitHub.
(still to be updated for 4.0.0 - 20180322)

These have models for legacy tesseract engine (--oem 0) as well as the new LSTM neural net based engine (--oem 1).

The LSTM models (--oem 1) in these files 
have been updated to the integerized versions of 
[tessdata_best](https://github.com/tesseract-ocr/tessdata_best) on GitHub.
So, they should be faster but probably a little less accurate than tessdata_best.

[tessdata_fast](https://github.com/tesseract-ocr/tessdata_fast) on GitHub
provides an alternate set of integerized LSTM models which have been built with a smaller network.
tessdata_fast files are the ones packaged for Debian and Ubuntu.

The legacy tesseract models (--oem 0) have been removed for Indic and
Arabic script language files.

tessdata for 3.04 or 3.05
-------------------------

Get language data files for Tesseract 3.04 or 3.05 from the
[3.04 tree](https://github.com/tesseract-ocr/tessdata/tree/3.04.00).

More information and a complete list of all languages is available in the
[Tesseract wiki](https://github.com/tesseract-ocr/tesseract/wiki/Data-Files).

All data in the repository are licensed under the
Apache-2.0 License, see file [LICENSE](LICENSE).
