Before you can flash the **{{ $device.name }}** with resinOS, you'll need to prepare it with the latest [JetPack](https://developer.nvidia.com/embedded/jetpack) using the instructions provided by [Nvidia](http://docs.nvidia.com/jetpack-l4t/3.1/index.html#developertools/mobile/jetpack/l4t/3.1/jetpack_l4t_install.htm).

Once this is finished, make sure your **{{ $device.name }}** development board is powered off. Insert the SD card you've flashed with resinOS and plug in the power cord. Press and hold the power button for one second to turn the device on. 

__Note:__ This will also completely erase internal storage media, so please make a backup first.

<img src="/img/tx2devboard.png" width="40%">

At this point your device will attempt to connect to the internet. If you selected WiFi as your connectivity type, remember to attach the WiFi antennas before booting the board. If you selected ethernet, make sure your ethernet cable is plugged in. Your device should show up on the dashboard in 10 minutes or less.

After the device has been provisioned, it will shut itself off automatically. You can safely remove the SD card. 

Your **{{ $device.name }}** is now ready to run an application. Press the power button once more to turn it on, and get ready to make your first code deploy!