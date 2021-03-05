# ZIRCONIUM

ZIRCONIUM has been created to scan for Indicators of Compromise (IOCs) on Exchange Servers for signs of
Zero-Day exploits used by HAFNIUM. 

ZIRCONIUM will search for:
* CVE-2021-26855
* CVE-2021-26958
* CVE-2021-26857
* CVE-2021-27027065
* Suspicious .dmp Files
* .aspnet Files Found in inetpub and Exchange File Paths

## Usage

Download the lastest version of ZIRCONIUM: https://github.com/SpearTip-Cyber-Counterintelligence/Zirconium/releases/download/1.0/Zirconium.exe

Move the latest version of ZIRCONIUM to your desktop and double click the application to start.
ZIRCONIUM will begin to scan the system, outputting notification balloons to the bottom right-hand
corner of the screen.


Once ZIRCONIUM has completed its scan, you will find a .txt file on your desktop labeled "ZIRCONIUM-Info.txt"
that contains any information the application has found, including possible compromise, bad filepaths, etc.
