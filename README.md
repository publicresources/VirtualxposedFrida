# VirtualXposedFrida
Virtual xposed frida is an aplication that implement frida for instrumentation, this virtual auto run the gadget on the startup of any aplication inside of the virtual, making it be possible to run tests on non rooted device without repacking the apk, breaking the signature 

just add your target on the app then you can play with it :)

#Note
the target aplication will be black screen, because its the gadget awaiting for a frida iteracrion.

#Iteration example
usb
```
frida -U -n "Gadget" -l yourscript.js
```
