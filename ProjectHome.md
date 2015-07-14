Java QRcode reader with ZBar, JNative & DSJ.

ZBar has it's own JNI interface, but it's not compiled in by default.


And its default video capture interface does not work on my high-definitioned WebCam, either. So I created this project, using dsj for video capture and ZBar for decoding.

It works for Windows(R) only .