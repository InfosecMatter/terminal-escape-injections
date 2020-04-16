# Terminal escape injection PoCs

This repository contains sample PoC codes demonstrating the terminal escape injection vulnerability which affects all modern systems including:
- Microsoft Windows 10
- Mac OS
- Linux

See the main article here: https://www.infosecmatter.com/terminal-escape-injection/


### Terminal injection in a shell script:
![esc-inject-shell-linux-gnome-terminal](https://user-images.githubusercontent.com/60963123/79501079-85d6dc80-803e-11ea-8cee-f7e1755c7551.png)

Tested on:
- Linux (gnome-terminal, xterm, aterm)
- Mac OS (Terminal 2.0, iTerm2)
- Cygwin (Windows)

### Terminal injection in a python script:
![esc-inject-python-mac-terminal](https://user-images.githubusercontent.com/60963123/79501309-e1a16580-803e-11ea-8b2e-e01b105bfc4d.png)

Tested on:
- Linux (gnome-terminal, xterm, aterm)
- Mac OS (Terminal 2.0, iTerm2)
- Cygwin (Windows)

### Terminal injection in a batch (.bat) file:
![esc-inject-bat-win-cmd](https://user-images.githubusercontent.com/60963123/79501363-f7168f80-803e-11ea-9104-0bfd8211b62e.png)

Tested on:
- Windows 10 PowerShell
- Windows 10 Command Prompt

### Terminal injection in a PowerShell (.ps1) script:
![esc-inject-ps1-win-powershell](https://user-images.githubusercontent.com/60963123/79501421-10b7d700-803f-11ea-83d7-d2181e9692de.png)
Tested on:
- Windows 10 PowerShell
- Windows 10 Command Prompt

For more information, visit https://www.infosecmatter.com/terminal-escape-injection/
