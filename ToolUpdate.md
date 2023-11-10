example update command:
./fw-update -s 725112060411 -f Firmware/FW_UVC_5_11_6_250.bin

List all device
./fw-update -l

note:
 -s <string>	Camera Serial number
 -f <string>	Frimware file
 -b <string>	Backup frimware
 -l  		List all camera



Steps to Update:

1.Clone the git folder to Stride
	git clone https://github.com/Deepanys/RV_FW_UPDATER.git

	cd RV_FW_UPDATER

2.Revoke Executable permission
	chmod +x fw-update

3.Check connected devices
	./fw-update -l

4.Update firmware
	./fw-update -s SerialNumber -f Firmware/firmware.bin

5.Check firmware version
	./fw-update -l
	