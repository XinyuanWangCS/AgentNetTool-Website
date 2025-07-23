# Freqently Asked Questions (FAQs) for Mac


## OBS Setting
### **1. "Starting the output failed...If you are using the NVENC or AMD encoders, make sure yourvideo drivers are up to date."**
<img src="../assets/start_output_failed_1.png" style="zoom:50%;display:inline" />
??? info "Solution"
    1. Quit OBS and the annotator app, and restart them;
    2. If it still doesn't work, go to OBS, click 'Setting'
    <img src="../assets/obs_setting.png" style="zoom:50%;" />
    3. Go to 'Output' and make sure the 'Output Mode' is simple
    <img src="../assets/obs_output_mode.png" style="zoom:50%;" />
    4. Scroll down to the section or 'Recording', check the Video Encoder. If your current encoder is Software, change it to hardware, otherwise change it to software.
    <img src="../assets/change_encoder.png" style="zoom:50%;" />
    5. Quit OBS and annotator app, restart them.

### **2. Backend: start record failed. authentication enabled but no password provided**
<img src="../assets/faq11.jpg" style="zoom:25%;" />

??? info "Solution"
    Check Setup OBS Websocket Server part, make sure 'Enable Authentication' is unchecked.



## Unable to upload data
### **1. When you click upload, if the following message is shown**
<img src="../assets/upload_failed.png" style="zoom:70%;" />
??? info "Solution"
    1. Check your network connection. You might need a VPN.
    2. Make sure the video is not too long (e.g. more than 15mins)


## Can't stop recording. It keeps processing.
<img src="../assets/cannot_stop_recording.png" style="zoom:25%;" />
??? info "Solution"
    1. This might happen the first time you start the app and finsih your OBS setup. Please restart OBS and the app and try again.
    2. If your recording is about the Calendar app on Mac, record another piece of data that avoids Calendar app (eg. website task). If this time it works, please avoid recoridng Calendar tasks for now.
