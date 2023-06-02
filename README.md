# CLI-colors


    Command Prompt (cmd):
        To change the text color: color <hex_value>
        To change the background color: color <background_hex_value>
        To clear the screen: cls

    PowerShell:
        To change the text color: Write-Host -ForegroundColor <color> "Text"
        To change the background color: Write-Host -BackgroundColor <color> "Text"
        To clear the screen: Clear-Host

    Bash (Unix/Linux):
        To change the text color: echo -e "\e[<attribute>;<foreground_color>mText\e[0m"
        To change the background color: echo -e "\e[<attribute>;<background_color>mText\e[0m"
        To clear the screen: clear

    Zsh (Z shell):
        To change the text color: echo -e "%{<attribute>;<foreground_color>%}Text%{\e[0m%}"
        To change the background color: echo -e "%{<attribute>;<background_color>%}Text%{\e[0m%}"
        To clear the screen: clear
        
    
    Orange:
        Hexadecimal: #FFA500
        cmd: color 6
        PowerShell: Write-Host -ForegroundColor "Orange" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[33mText\e[0m"

    Yellow:
        Hexadecimal: #FFFF00
        cmd: color E
        PowerShell: Write-Host -ForegroundColor "Yellow" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[93mText\e[0m"

    Blue:
        Hexadecimal: #0000FF
        cmd: color 1
        PowerShell: Write-Host -ForegroundColor "Blue" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[34mText\e[0m"

    Green:
        Hexadecimal: #00FF00
        cmd: color A
        PowerShell: Write-Host -ForegroundColor "Green" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[32mText\e[0m"

    Red:
        Hexadecimal: #FF0000
        cmd: color 4
        PowerShell: Write-Host -ForegroundColor "Red" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[31mText\e[0m"

    White:
        Hexadecimal: #FFFFFF
        cmd: color F
        PowerShell: Write-Host -ForegroundColor "White" -BackgroundColor "Black"
        Bash/Zsh: echo -e "\e[97mText\e[0m"
