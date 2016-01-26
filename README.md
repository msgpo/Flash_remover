Unofficial Adobe Flash Player removal solution by CHEF-KOCH
----------

This is an Adobe Flash Player uninstall solution especially for Windows 10 which also should remove the native support. 


Basic and official uninstaller commands:
* ActiveX Control: <code>uninstall_flash_player.exe -uninstall activex</code>
* NPAPI Plugin: <code>uninstall_flash_player.exe -uninstall plugin</code>
* Silent uninstaller: <code>uninstall_flash_player.exe -uninstall</code>


Linux only:
rpm -e flash-plugin
yum remove flash-plugin
apt-get remove flash-plugin


Official:
- Contains always the latest flash uninstaller : https://helpx.adobe.com/flash-player/kb/uninstall-flash-player-windows.html This tool will be updated after each new Adobe Flash Player release. The Problem is that it not remove the native WIndows Flash support or all of is registry detection keys.

Test:
- Test folder




Research:
* https://www.adobe.com/devnet/flashplayer/articles/flash_player_admin_guide.html


Todo:
- More project info
- Small script to automatically remove all this Adobe FLash Player stuff
- .... 
 
