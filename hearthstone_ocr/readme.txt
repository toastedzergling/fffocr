This script will not work on windows without modification of the code. If you don't have experience working with perl, don't even bother.

LIBS/PROGRAMS YOU NEED:
 http://code.google.com/p/tesseract-ocr/ - You need a working installation of tesseract for this script to work. 
 http://livestreamer.tanuki.se/en/latest/ - livestreamer to grab the twitch stream (can be done without livestreamer, but for now my own code to grab the twitch stream isn't as stable, so this will have to do)
 http://curl.haxx.se/ - curl is a command line tool for transferring data with URL syntax, supporting DICT, FILE, FTP, FTPS, Gopher, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMTP, SMTPS, Telnet and TFTP.

Files in tesseract_config/ should be set up like this: (required for OCR to work properly with HS)
 eng.user-words moved to /usr/share/tessdata/eng.user-words (or equivalent)
 hearthstone_classvictory moved to /usr/share/tessdata/configs/hearthstone_classvictory (or equivalent)

Perl modules needed for the hs_ocr script to work: (download at cpan.org)
 Image::Magick - image processing module
 Modern::Perl - not REALLY needed, but, get it.

CONTACT:
 I might have forgotten something, if you have any problems you can always join trump's twitch chat and ask "ImHid" for help, although I do not promise I will respond or have the time to help you. There is absolutely zero support guaranteed for this program and you use it completely at your own discretion.
