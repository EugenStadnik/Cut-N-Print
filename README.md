# Cut-N-Print
Script to cut image to current printer media size and then print it.

!!!THIS SCRIPT WORKS ONLY WITH POSIX LIKE OPERATION SYSTEMS!!!

ABOUT:
This script parces media settings of current default printer, cuts selected image evenly to fit it exactly to media size and prints cuted image using current printer settings.
So take note about settings of printer. Also this script doesn't change selected image, it creates temporary image and then, after successful print, this script deletes temporary image.

PRESETTINGS:
This script requires awk, convert from ImageMagik package, identify, lpoptions, sed, lp, date, basename, tee, echo, bash and also zenity linux commands to be installed befor deploy of this script.
If yor /home/user/bin dyrectory is mentioned in PATH global environment variable this script will work from any place of your file system.

DEPLOY:
To deploy this script just install previously mentioned posix commands using either apt or yum or pkg or in any other avalable way then just copy content of this folder to your /home/user/ dyrectory.

USE:
To use this script just type it's name in system shell like this "$ cutNprint" and pass all images you need to cut and print as argument list.

MORE:
In the future I have many plans about improvements of this script. So feel free to contact me using this site.