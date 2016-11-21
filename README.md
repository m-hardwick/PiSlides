# PiSlides
A set of scripts for loading, reloading and displaying slides on Raspberry Pi

Name: checktmp.sh
Use: Displays the CPU temp
Usage Example: ./checktmp.sh

Name: ffmpeg_jpg.sh OR prep_jpg.sh
Use: Transcodes /home/pi/ImagePrep/slide000.jpg to slide999.jpg into /home/pi/Prep/slides.h264
Usage Example: ./ffmpeg_jpg.sh OR ./prep_jpg.sh

Name: ffmpeg_JPG.sh or prep_JPG.sh
Use: Transcodes /home/pi/ImagePrep/Slide000.JPG to slide999.jpg into /home/pi/Prep/slides.h2
64
Usage Example: ./ffmpeg_JPG.sh OR ./prep_JPG.sh

Name: transcodefile_jpg.sh
Use: Transcodes the specified file from /home/pi/ImagePrep , The filename must end in "000.jpg"
Usage Example: ./transcodefile_jpg.sh slide (Based on a filename of slide001.jpg)
Usage Example: ./transcodefile_jpg.sh Slide (Based on a filename of Slide001.jpg)

Name: transcodefile_JPG.sh
Use: Transcodes the specified file from /home/pi/ImagePrep , The filename must end in "000.jpg"
Usage Example: ./transcodefile_jpg.sh slide (Based on a filename of slide001.JPG)
Usage Example: ./transcodefile_jpg.sh Slide (Based on a filename of Slide001.JPG)

Name: reboot_alltv.sh
Use: Reboot alltvs
Usage Example: ./reboot_alltv.sh (Edit hosts with nano ~/TVs/alltv)

Name: psshreboot_officetvs.sh
Use: Reboot all TVs in parallel
Usage Example: ./psshreboot_officetvs.sh (Edit hosts with nano ~/TVs/officetvs)

Name upload.sh
Use: Upload ~/Prep/slides.h264 to ~/loopcontent on all machines (Edit hosts with nano ~/TVs/alltv)
Usage Example ./upload.sh

Name: reload_officetvs.sh
Use: Stop's the current slideshow and loads the new one. (Edit hosts with nano ~/TVs/officetvs)

Name: reload_publictvs.sh
Use: (Edit hosts with nano ~/TVs/publictvs)
