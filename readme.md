### This readme is for preparing little MAME arcade game box with RetroPie and Raspberry Pi 3

# Download 
wget -bqc https://github.com/RetroPie/RetroPie-Setup/releases/download/4.1/retropie-4.1-rpi2_rpi3.img.gz

tar xzf retropie-4.1-rpi2_rpi3.img.gz

dd if=retropie-4.1-rpi2_rpi3.img of=<SD-card device> bs=1m

# MAME 2003 0.78 ROM set for RPi 2/3 (RetroPie)
wget -bqc https://ia801506.us.archive.org/zip_dir.php?path=/33/items/MAME2003_Reference_Set_MAME0.78_ROMs_CHDs_Samples.zip&formats=ZIP

unzip MAME2003_Reference_Set_MAME0.78_ROMs_CHDs_Samples.zip

# Copy the MAME ROMs to /home/pi/RetroPie/roms/mame-libretro if you are on Linux
# Transfer the ROMs to roms/mame-libretro via Samba if you are on Mac OS X or Windows