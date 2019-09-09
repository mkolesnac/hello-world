# KMS Client Setup Keys
Computers that are running volume licensing editions of Windows 10, Windows 8.1, Windows Server 2012 R2, Windows 8, Windows Server 2012, Windows 7, Windows Server 2008 R2, Windows Vista, and Windows Server 2008 are, by default, KMS clients with no additional configuration needed.

To use the keys listed here (which are GVLKs), you must first have a KMS host running in your deployment. If you haven’t already configured a KMS host, see Deploy KMS Activation for steps to set one up.

If you are converting a computer from a KMS host, MAK, or retail edition of Windows to a KMS client, install the applicable setup key (GVLK) from the following tables. To install a client setup key, open an administrative command prompt on the client, type slmgr /ipk <setup key> and then press Enter.

If you want to…
	

…use these resources

Activate Windows outside of a volume-activation scenario (that is, you’re trying to activate a retail version of Windows), these keys will not work.
	

Use these links for retail versions of Windows:

    Install, upgrade, & activate (use the menu to the right to select the Windows version you are interested in)

    Get a new Windows product key

    Genuine Windows Help & How-to

    Microsoft Community forum on installation and activation

Fix this error that you get when you try to activate a Windows 8.1, Windows Server 2012 R2 or newer system: “Error: 0xC004F050 The Software Licensing Service reported that the product key is invalid”…
	

Install this update on the KMS host if it is running Windows 8.1, Windows Server 2012 R2, Windows 8, or Windows Server 2012.

If you are running Windows Server 2008 R2 or Windows 7, be on the lookout for an update to support using those as KMS hosts for Windows 10 clients.
