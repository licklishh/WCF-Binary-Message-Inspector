WCF Binary Message Inspector
============================

This is a modification of the [waf/WCF Binary Message Inspector](https://github.com/waf/WCF-Binary-Message-Inspector). 

Breaking Changes:
---------------
Changed to use .NET Binary Format: SOAP Data Structure [Protocol 5.0](https://msdn.microsoft.com/en-us/library/cc219175.aspx), used to view Content-Type: application/soap+msbin1

Todo: Changed panel name to coexist with original plugin / integrate into same plugin, until then this is not compatiable with original WCF Binary Message Inspector.

Download DLL [Here](https://github.com/licklishh/WCF-Binary-Message-Inspector/raw/master/BinaryMessageFiddlerExtension/bin/Release/BinaryMessageFiddlerExtension.dll).

Tree View Usage
---------------

The tree view provides the following shortcuts:

* Ctrl+c — Copy current node XML
* Ctrl+Shift+c — Copy tree XML
* Alt+→ — Expand node and all child nodes
* Alt+← — Collapse node and all child nodes
* Middle-click — Toggle expand/collapse of node and all child nodes

Edit Usage
----------

1. Capture a WCF binary message
2. In the sessions list, right click on the message and choose "Unlock for editing"
3. Edit the request 
4. Reissue the request using the toolbar or the session list context menu

Development
-----------

The project is a Visual Studio 2010 project, and requires a reference to your `Fiddler.exe` file in order to compile.

See [Fiddler's page on Custom Inspectors](http://www.fiddler2.com/Fiddler/dev/Inspectors.asp) for more information.
