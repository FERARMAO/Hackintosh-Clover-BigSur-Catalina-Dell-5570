# Hackintosh-Clover-BigSur-Catalina-Dell-5570
This is a post-install EFI folder based on Clover bootloader for macOs Big Sur and Catalina on a hackintosh pc.
You can download Vanilla iso images for Big Sur or Catalina from [OLARILA website](https://www.olarila.com/topic/6278-olarila-vanilla-images/) and download [balenaEtcher](https://www.balena.io/etcher/) to create a bootable usb drive to be able to install the OS of your choice.

Laptop specifications :
- CPU : Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz
- RAM : 8GB DDR4 2400 Mhz
- SSD : samsung ssd 850 evo 250 go 
- GPU : Intel UHD Graphics 620

What is working : 
- Graphics acceleration
- audio/ microphone/ audio control (F2 & F3)
- trackpad
- display brightness/ brightness control (F11 & F12)
- battery managment
- sleep/wake

### EFI 
Basically you just have to download the EFI folder by clicking on "clone or download", or you can open your terminal and type the following command :
``` git clone https://github.com/FERARMAO/Hackintosh-Clover-BigSur-Catalina-Dell-5570.git ```
Then mount your EFI partition, open it, and put the EFI folder there. (replace if there is an existant EFI folder)
That's pretty much it, now restart your laptop.
Happy hackintoshing :)