duplex-printing
===============

Simple shell script for manual duplex printing. Linux drivers for some printers do not allow manual duplex printing. This simple shell script allows duplex printing from the command line. The program is called as follows:

./pduplex -p 190-201 -f '/home/Documents/file_name.pdf'

The tag -p indicates the page range that will be printed.
The tag -f indicates the full path of the document to be printed. 

After executing the program you have to wait until all the back side pages are printed. Then place the printed pages as returned by the printer into the paper tray to print the front side pages. A dialog from the command line  will ask you to type 'c' and enter to continue.   

This script has been tested with a printer HP LaserJet P1102w.
