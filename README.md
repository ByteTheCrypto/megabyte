import xbmc
import xbmcaddon
import sys

addon = xbmcaddon.Addon()
message = "Hello from YOUR_NAME! This is running from plugin.program.helloworld."

# Show a dialog
dialog = xbmcgui.Dialog()
dialog.ok("Hello World Addon", message)

# Exit cleanly
sys.exit(0)
