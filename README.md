# Ajaxey

This is a "fork" of the amazing work [[W4RH4WK]](https://github.com/W4RH4WK/Debloat-Windows-10) has made over the years. It has the same clear goal: to clean the sh1t out of Microsoft Windows of its unneseaseary apps, **tweaking it for my needs**. 
Hence the alusion to popular window cleaner Aj4x. :]

## How does it work
Basicaly you just run a script on PowerShell, and voilá! Got your Windows cleaned up. 

**A COUPLE OF NOTES**
1. Mind you that you need to make sure it doesn't delete anything you don't want to;
2. I only use [[like W4RH4WK]](https://github.com/W4RH4WK/Debloat-Windows-10) Microsoft Windows Pro 64-bit. "Home Edition and different languages are not supported".

## Download Latest Version

So far it's only meant to remove some apps from my machine, but I'll be posting stuff as I get my hands dirtier and Microsoft Windows Cleaner.
Code located in the `master` but it's easier to download the full cleaning package as it unfolds.

- [Download [zip]](https://github.com/opedromandrade/ajaxey/archive/master.zip)

## How to clean up

Enable execution of PowerShell scripts:

    PS> Set-ExecutionPolicy Unrestricted -Scope CurrentUser

Unblock PowerShell scripts and modules within this directory:

    PS> ls -Recurse *.ps*1 | Unblock-File

## Usage

Scripts can be run individually, pick what you need.

1. Install all available updates for your system.
2. Edit the scripts to fit your need.
3. Run the scripts you want to apply from a PowerShell with administrator privileges (Explorer
   `Files > Open Windows PowerShell > Open Windows PowerShell as
   administrator`)
4. `PS > Restart-Computer`
5. Run `disable-windows-defender.ps1` one more time if you ran it in step 3
6. `PS > Restart-Computer`

## WARNING
These scripts come with absolutly no kind of warranty or support. It may bork your system. Use it to your own fruition, but caution is advised.

## License

 * ----------------------------------------------------------------------------
 * "THE BEER-WARE LICENSE" (Revision 42):
 * <phk@FreeBSD.ORG> wrote this file.  As long as you retain this notice you
 * can do whatever you want with this stuff. If we meet some day, and you think
 * this stuff is worth it, you can buy me a beer in return.   Poul-Henning Kamp
 * ----------------------------------------------------------------------------