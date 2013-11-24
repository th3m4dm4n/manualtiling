###Manual Tiling

Manual Tiling is a simple theme for awesome WM (v.3.4 or below) basedthe the default theme.


How to install:
---------------
###1.Install Tewi (recommended)* 
	You can get it here:
	https://github.com/neeee/tewi-font

###2. Install manualtiling
	Clone this repo to /usr/share/awesome
	
###3. Set it as default theme
	Search for "beautiful.init" in "/etc/xdg/awesome/rc.lua" and change it to look like this:

		-- {{{ Variable definitions
		-- Themes define colours, icons, and wallpapers
		beautiful.init("/usr/share/awesome/themes/manualtiling/theme.lua")
		 

###4. Restart awesome

*manualtiling uses tewi is default font, you can always choose to use another font
