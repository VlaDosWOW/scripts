**Install Wifi Driver in Ubuntu 18.04 for hp laptop 15**

`sudo apt install git build-essential dkm`

`sudo apt-get install git`

`git clone -b extended https://github.com/lwfinger/rtlwifi_new.git`

`sudo dkms add ./rtlwifi_new`

`sudo dkms install rtlwifi-new/0.6`

`sudo modprobe -r rtl8723de && sudo modprobe rtl8723de`
