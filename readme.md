## A PowerShell IDE and terminal for the browser

This is a proof-of-concept PowerShell IDE/terminal for the browser, built with Node.js. Theoretically, if Powershell is installed on a Linux or macOS device, this app should work. It can be used to demonstrate vulnerabilities and remote Powershell execution capabilities.  It should not be used for anything else.

![Powershell IDE screenshot 1](https://raw.githubusercontent.com/RussellWebSystems/powershell-ide/master/images/pside1.png "Powershell IDE editor with autocomplete")
![Powershell IDE screenshot 2](https://raw.githubusercontent.com/RussellWebSystems/powershell-ide/master/images/pside2.png "Powershell IDE script editor results")
![Powershell IDE screenshot 3](https://raw.githubusercontent.com/RussellWebSystems/powershell-ide/master/images/pside3.png "Powershell IDE terminal")

The app consists of two tabs, a terminal and a script pane. When you run the code in the script pane, the output appears in a modal pop-up.

In the script pane, press ctrl+space for autocomplete.

To try it out, clone the project:

`git clone https://github.com/RussellWebSystems/powershell-ide.git`

Install the node module dependencies:
	
`cd powershell-ide && npm install`

Run the app:

`node server.js`

And finally, go to http://localhost:7979/ in your web browser.
