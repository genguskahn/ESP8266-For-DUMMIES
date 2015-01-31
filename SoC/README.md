#README FIRST...

For ANY of the items in this folder tree to function the NodeMCU firmware MUST FIRST be loaded.

------------------------------------------------------------------------------------------------

Read the text file Init.Lua in Examples Folder, this is the Webserver it explains that...

The WiFi MUST be set first, this only needs doing when you FLASH firmware.

The File LuaLoader.png shows how to set SSID & PAASSWORD for the WifI.

Just enter the details and click "Set AP".

Then Click "Upload file", find "init.lua" click OPEN.

When complete click "Restart".

Sometimes it is best at this point to remove the power to allow a "COLD" boot(Complete RESET).

When the module is powered up it now serves a web page to the IP assigned to the WiFi
.

If you have problems with GPIO_X pins as an output See GPIO_BUFFER.jgp.



