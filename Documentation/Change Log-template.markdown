Change Log
==========

This is the history of version updates.

**Version 1.4.3**

- FIXED: Removed Error in DTWeakSupport, as including this in non-ARC project is legitimate use

**Version 1.4.2**

- ADDED: DTWeakSupport.h for tagging variables and properties to use weak refs if supported
- FIXED: [DTSidePanel] classes missing from static library target
- CHANGED: Implemented conditional weak support in DTSidePanelController, DTActionSheet, DTAlertView, 
DTSmartPagingScrollView, DTHTMLParser, DTASN1Parser

**Version 1.4.1**

- ADDED: [DTCustomColoredAccessory] Added left arrow disclosure indicator
- ADDED: [DTReachability] Demo App
- CHANGED: [DTReachability] to observe reachability to apple.com instead of general IP connectivity as this addresses some issues where DNS resolving might lag behind
- FIXED: [DTSidePanel] Appearance Notifications not sent to replaced panels

**Version 1.4**

- ADDED: [DTSidePanel] Container Controller
- ADDED: [DTSQLite] Wrapper class for SQLite3 Databases
- ADDED: [DTAlertView] Method to create a cancel button and/or set a cancelBlock.
- CHANGED: Moved experimental striped layer into Experimental folder

**Version 1.3**

- ADDED: [DTReachability]
- FIXED: [DTZipArchive] Incorrect Define

**Version 1.2**

- ADDED: [DTASN1] BitString support
- ADDED: [DTASN1] DTASN1Serialization
- ADDED: [DTASN1] IA5 String support
- FIXED: [DTZipArchive] Unit Tests

**Version 1.1**

- CHANGED: Refactored base64 methods into DTBase64Coding
- ADDED: UIView Debug methods to catch errors where UIView methods are called on background thread
- ADDED: [Experimental] DTStripedLayer
- ADDED: Method to produce random color
- ADDED: DTTiledLayerWithoutFade
- ADDED: CGRectCenter
- FIXED: [AppKit] Fixed bugs in panel presenting
- CHANGED: [DTZipArchive] Various Improvements
- CHANGED: [DTUTI] Moved to separate library/subspec
- REMOVED: DTDownload and DTBonjour, they become their own repositories
