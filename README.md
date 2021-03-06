# Doc InSight


Doc InSight provides an augmented reality heads-up display for health care professionals. Relevant medical information from an electronic health record is displayed in the wearer's field of vision when environmental QR codes are detected. The information display is completely passive and hands-free -- no action is required of the user.

## Overview

- https://www.youtube.com/watch?v=gUhW3h4iEiE

![Overview](https://raw.githubusercontent.com/nickbild/nickbild79_firebase/master/public/img/doc_insight_1.png)

![Overview](https://raw.githubusercontent.com/nickbild/nickbild79_firebase/master/public/img/doc_insight_3.png)

## Dependencies

- https://opencv.org/releases.html
- http://zbar.sourceforge.net/download.html
- https://www.sqlite.org/index.html

## Usage

To start Doc InSight, simply execute the compiled binary without parameters.

By default, webcam device 0 will be used. If you need to change the device ID, do so in qr.cpp.

Barcode information is stored in the SQLite3 database named "qrdb.db". Add your barcodes here to
display information when they are detected by the webcam.

## Further Information

https://nickbild79.firebaseapp.com/#!/drdata

