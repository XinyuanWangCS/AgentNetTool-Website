# Freqently Asked Questions (FAQs) for Windows

## Unable to start the App
### **1. When you try to start the app, if the following window pops up**
<img src="../assets/js_error.png" style="zoom:50%;" />
??? info "Solution"
    1. Press `Ctrl+Shift+Esc` to open Task Manager of your computer
    2. Right-click agentnet-annotator and select End Task
    3. Check your OBS is [30.1.2](https://drive.google.com/file/d/1gas-fR4HJdp2_k8JtqTC98SBRA9sxWJV/view) and is correctly setup. Start OBS before you start the annotator app.
    4. Restart the app.
    !!! warning
        Sometimes, it takes a few seconds to start the app. Just wait for the app's window to show up and don't try to click the app repeatedly.

## OBS Setting
### **1. "Starting the output failed...If you are using the NVENC or AMD encoders, make sure yourvideo drivers are up to date."**
<img src="../assets/start_output_failed_2.png" style="zoom:30%;" />
??? info "Solution"
    1. Try to quit OBS and the annotator app, and restart them to see if it works;
    2. If it still doesn't work, go to your OBS, click 'Setting'
    <img src="../assets/obs_setting.png" style="zoom:50%;" />
    3. Go to 'Output' and make sure the 'Output Mode' is simple
    <img src="../assets/obs_output_mode.png" style="zoom:50%;" />
    4. Scroll down to the section or 'Recording', check the Video Encoder. If your current encoder is Software, change it to hardware, otherwise change it to software.
    <img src="../assets/change_encoder.png" style="zoom:50%;" />
    5. Quit OBS and annotator app, and restart them to see if it works.

### **2. Backend: start record failed. authentication enabled but no password provided**
<img src="../assets/faq11.jpg" style="zoom:25%;" />
??? info "Solution"
    Check Setup OBS Websocket Server part, make sure 'Enable Authentication' is unchecked.

## Unable to upload data
### **1. When you click upload, if the following message is shown**
<img src="../assets/upload_failed.png" style="zoom:70%;" />
??? info "Solution"
    1. Check your network connection. You might a need VPN.
    2. Make sure the video is not overly long (eg. more than 15mins)

## Can't stop recording. It keeps processing.
<img src="../assets/cannot_stop_recording.png" style="zoom:25%;" />
??? info "Solution"
    This might happen the first time you start the app and finsih your OBS setup. Please restart OBS and the app and try again. 


