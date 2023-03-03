## Contact Us Page 

This is a contact us page app which takes user's query and send the data to info@redpositive.in 


<img src="https://github.com/ajaman190/Redpositive-Service-App-Task/blob/master/Media/Screenshot_20230303-100937.png"  width="350">

## Installation

### Backend
Download the "Task_Backend" folder and open it in vscode.

```bash
  npm install
  npm run dev
```

### Frontend
Download the "Task_Frontend" folder and open it in vscode. Next, connect your Android device to your computer using a USB cable and ensure that USB debugging is enabled on your device. Alternatively, you can use an emulator instead of an Android device. Finally, run the commands

```bash
  npm install
  npm run android
```
Now to establish communication between the backend server running on localhost on your desktop and the app running on your Android device, run the below command in the terminal after building the app.

```bash
  adb reverse tcp:4000 tcp:4000
```
This 'adb reverse' command is used to set up reverse port forwarding between a device and a computer. In this case, it forwards TCP traffic from port 4000 on the computer to port 4000 on the device.
    
