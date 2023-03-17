# Vb6NotifyIcon
This is a class that wraps the Shell_NotifyIconA api and allows to put an icon in the windows notification area, this class uses the structure NOTIFYICONDATA version 4, and allows to show notifications with a custom icon (48px*48px) and allows to show a custom window replacing the tooltip standard.

### v1.5
By default icons are displayed using UID, a random GUID is no longer generated, to display an icon using a GUID you must assign the GUID to the class using the GUID property

Thanks to Leandro Ascierto for the GetScreenDPI function

 ![ITypeComp::Bind](/screens/nid00.jpg)
 
 ![ITypeComp::Bind](/screens/nid01.jpg)
 
 ![ITypeComp::Bind](/screens/nid03.jpg)
	
 ![ITypeComp::Bind](/screens/nid04.jpg)
 