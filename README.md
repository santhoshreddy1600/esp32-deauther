# esp32-deauther
download esp32 flasher https://docs.espressif.com/projects/esp-test-tools/en/latest/esp32/production_stage/tools/flash_download_tool.html  
after dowloading the flaher extract all the files and you will get flah 3.9.9 
go the flaher and slect esp32 and after going to flash connect your esp 32 with com port connect the port 
download the bin files prodivide by me 
frist bootloader.bin and enter the range 0x1000 beside a samll box provided press 3dots provided to upload files 
second partition-table.bin and the range is 0x8000
third hydra.bin and the range is 0x10000  
now select all the 3 boxes you filled with files and set the buad range 115200 and sip speed is 40mhz
now press start the code will be uploaded 
after uploading press rst or en button provided on esp 32 now a wifi is visible with SSID Hydra32
SSID:Hydra32
password: notforfun
connect it and go to any browser and search 192.168.4.1 and you wull get a interface 
from there you need to tap on the network you selected and tap on deauther below and enable timer or not 
this is for educational purpose
