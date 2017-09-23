# CertiGravi
You need to install graphicsMagick on the server first [GraphicsMagick](http://www.graphicsmagick.org/)<br/>Refer this for the rest http://aheckmann.github.io/gm/
<br/><br/>
Incorporated both, a form at the "/" path and a request route at "/req"<br/>
Parameters to fetch the overlayed image would be <br/>
```
/req?name=Kushagra Vaish&event=Mozilla Firefox WOrkshop
```
<br/>
Thing unimplemented would be
<br/>1. Image output stream can be cleared after every transaction
<br/>2. pdf conversion would be easy, using node-canvas [Mentionned Yesterday]

<br/> Beware! Highly hard coded :p
