pada proxy au1, au2, au3" dikarenakan portnya, bukam 443/80, maka di bagian path di exlave apk/ httpcustom apk, dll, harus di ganti seperti ini:

misal:
170.64.152.77	 port:7443
152.67.101.72	port: 23010
192.9.190.80	port:23862

di ganti di bagian path (jalur websocket):

/vl?192.9.190.80=23862

atau seperti ini path:
/192.9.190.80=23862
