# fileReader-vs-objectUrl

* Just a personal test about what is the fastest way for load images from client side with vanilla javascript
    * example load thumbnails at upload images (with or without drag & drop)

--------------------------------------

### My conclusion was:
* **smaller** files *(8 file, totally ~1.9mb)*
    * createObjectUrl: faster a bit (~0.065sec)
    * FileReaderApi: enough fast (~0.395sec)
* **bigger** files *(3 file, totally ~10mb)*
    * createObjectUrl: alot faster (~0.08sec)
    * FileReaderApi: slow (~1.044sec)

----------------------------------------------

[![Test](http://img.youtube.com/vi/j9QuKtGNNuY/0.jpg)](http://www.youtube.com/watch?v=j9QuKtGNNuY)
