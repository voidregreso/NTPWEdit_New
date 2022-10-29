# NTPWEdit_New
## NTPWEdit Version 0.7 Modified by VoidRegreso

 NTPWEdit is a password editor for Windows NT based systems (like Windows 2000, XP, Vista, 7, 8, 10), it can change or remove passwords for local system accounts. This program can NOT decrypt passwords or change domain, Active Directory or Microsoft account passwords.

NTPWEdit changes passwords by direct modifying file C:\WINDOWS\SYSTEM32\CONFIG\SAM. When running, operating system blocks any access to this file, so password editor must be executed on another Windows copy.

Some methods for use this program:

    boot Windows PE environment from CD-ROM or flash-drive and launch NTPWEdit;
    boot command line rescue mode from Windows Vista or newer distribution media;
    attach hard drive to another computer, and edit passwords there;
    boot system from separate partition (if multiple OS are installed). 