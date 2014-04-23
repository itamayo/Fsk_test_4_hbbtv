FSK TEST-SUITE FOR HBBTV
-----------------------
This test suite is part of the article "*Reaching device around an HbbTV television*" written it by Mikel Zorrilla, Angel Martin, Iñigo Tamayo, Sean O’Halpin and Dominique Hazael-Massieux.

Due the limitation of HbbTV to overlap an application created audio with the broadcast signal, this experiments measure the interruption time since the broadcast signal is cut in the TV, until the broadcasted content is back after played the sound pattern, recognisable by the second screen device

For data encoding inside playable audio we have used a extended technique used by data transmission industry (dial modem, emergency systems) known as AFSK.

> We got the best result with the following parameters:
> 
> Baud rate: 300 Mark frequency: 1700HZ Space frecuency: 1060HZ

The audio enconding was created by [minimodem][1] application.

Transmitted data
----------------

> * LongURL : http://192.168.10.12/thisisatest/index11111111111111111111111111111111.html
> * ShortURL : http://bit.ly/1pZ4h0T

Result
-----
![enter image description here][2]


  [1]: http://www.whence.com/minimodem/
  [2]: img/result.png
