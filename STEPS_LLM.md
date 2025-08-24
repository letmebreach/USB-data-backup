# Guide for USB preparation and confidental data backup
## Description of the requirements
Collection of best practices of backing up simple document files from endpoints. Starting from USB preparation and automation for audit purposes. Application is implementing secure coding principles with obfuscation techniques, distributed by selfsigned or self sources.
use full suite of tools to prepare usb for backing up data(documents mostly), i want most seucre way of retrieving data when connecting the usb to the destination device, and also steps for preparation the usb. im using w11, can use robocopy and script must validate final hash agianst original files, for all of them.  The preparation must prepare keys encypt the usb and also prepare script(binary with some deobfuscation techniques that will be run on the endpoint with the documents to be backup from.). Further suggest and imporve all steps for best practices
1 - Format USB, encrypt  
Steps: 
2 - Create script for interactive selection of data of interest and target export location
3 - Secure execution of backup script on endpoint
3.1 - Script obfuscation, compilation, 2FA auth before running & decryption of USB before using it for backup
3.2 - Verification of proper disk encryption
4 - PS/Robocopy on windows AND Linux TODO 
5 - File integrity verification
6 - Use backups on linux dislocker
