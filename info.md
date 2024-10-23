This guide will work with ChromeOS 129+.
**Note:** Device data is wiped. Enable developer mode.

### Steps to Enable Developer Mode

1. Turn off your Chromebook.
2. Press and hold the **ESC** (Button 1, row 1) and **Refresh** (Button 4, row 1) buttons.
3. Press the **Power** button to turn it on.
4. When the screen appears, press **Ctrl** (Button 1, row 6) + **D** (Button 4, row 4).
5. Press **Enter**. The device may reboot a few times; if you see the screen again, just press **Enter**.
6. Connect to Wi-Fi and log in with your Google account.

### Set Up Linux Development

![Open Settings](linux_setup_1.png)
![Start Setup](linux_setup_2.png)
![Set Username](linux_setup_3.png)
![Install](linux_setup_4.png)
![Install Complete](linux_setup_5.png)

### Enable ADB Debugging

![Open Settings](enable_adb_1.png)
![Click on Develop Android Apps](enable_adb_2.png)
![Turn on Toggle](enable_adb_3.png)

### Turn on Wi-Fi Debugging in Android Instance

![Select Apps from Settings](enable_wifi_debug_1.png)
![Click Android Settings](enable_wifi_debug_2.png)
![Scroll Down to Developer Settings](enable_wifi_debug_3.png)

If not found, enable developer options by going to the About section and clicking on the Build Number 7 times.

![Open Developer Options and Scroll to ADB Debugging](enable_wifi_debug_4.png)
Turn on both ADB Debugging and Wi-Fi Debugging.

![Click on Wi-Fi Debugging and Make Note of IP](enable_wifi_debug_5.png)

### Connect from Development Machine

1. Install and start ADB on your development machine.
2. Try to connect using the IP copied from the Android instance.
   
![Connect from Dev Machine](dev_machine_1.png)
Allow the popup.

![Allow from ChromeOS](dev_machine_2.png)

You should be good to go!
