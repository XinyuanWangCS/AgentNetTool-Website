<link rel="stylesheet" href="../assets/style.css">
# Windows

## Installation Overview

To use our AgentNet annotation tool, you have to install and setup the following **3** tools:

1. **OBS** is used for recording your desktop screen.
2. **Browser Extension** is used for obtaining the webpage html data.
3. **AgentNet** is a our annotation app that uses OBS to record your desktop and browser extension to get the webpage html data.

## Step 1 OBS Setup

### 1. Download & Installation

#### 1.1 Download **OBS 30.1.2 version** from [this link](https://drive.google.com/file/d/1gas-fR4HJdp2_k8JtqTC98SBRA9sxWJV/view?usp=drive_link) (Please don't install other versions).

#### 1.2 Double click on: **OBS-Studio-30.1.2-Full-Installer-x64.exe**.

#### 1.3 Follow the instructions to install OBS, using the default setting.

<!-- [TODO]

<div style="text-align: center;">
    <img src="../windows_assets/obs0.png" alt="img" style="zoom:33%;">
</div> -->

### 2. Setup OBS Auto-Configuration

#### 2.1 Open OBS

#### 2.2 Skip Update: If you see "New update available", choose "Skip"

#### 2.3 Usage Information: Choose **Optimize just for recording**

#### 2.4 Video Setting: Click "Next"

#### 2.5 Final Results: Click "Apply Settings"

<div class="image-collection">
<div class="image-container">
 <img src="../windows_assets/obs1.png" alt="img" class="step-image">
 <div class="step-tag">2.2</div>
</div>
<div class="image-container">
 <img src="../windows_assets/obs3.png" alt="img" class="step-image">
 <div class="step-tag">2.3</div>
</div>
<div class="image-container">
 <img src="../windows_assets/obs4.png" alt="img" class="step-image">
 <div class="step-tag">2.4</div>
</div>
</div>

### 3. Setup OBS Websocket Server

#### 3.1 Click **"Tools"** select **"WebSocket Server Settings".**

#### 3.2 Check **"Enable WebSocket server"** and <span style="color:red;">**uncheck**</span> **"Enable Authentication."**, Click "Apply," then "Ok."

<div class="image-collection">
    <div class="image-container">
        <img src="../windows_assets/obs5.png" alt="img" class="step-image">
        <div class="step-tag">3.1</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/obs6.png" alt="img" class="step-image">
        <div class="step-tag">3.2</div>
    </div>
</div>

### 4. Add Display Capture

#### 4.1 Back on the home page of OBS, click **"Scene"**/**场景** in "Scenes" ①, click the **"+"** button ② and then click **"Display Capture"** ③. Keep clicking "OK" to create new source.

#### 4.2 You should see your **current desktop** screen on the canvas.

<div class="image-collection">
<div class="image-container">
    <img src="../windows_assets/obs7.png" alt="img" class="step-image">
    <div class="step-tag">4.1</div>
</div>
<div class="image-container">
    <img src="../windows_assets/obs8.png" alt="img" class="step-image">
    <div class="step-tag">4.1</div>
</div>
<div class="image-container">
    <img src="../windows_assets/obs9.png" alt="img" class="step-image">
    <div class="step-tag">4.2</div>
</div>
</div>

### 5. OBS Setup Tutorial Video (Optional)

Here's a tutorial video for all the steps mentioned. **Skip** if you've already followed the instructions.
<video width="500" controls>

  <source src="../windows_assets/windows_setup_obs.mp4" type="video/mp4">
</video>

## Step 2 Install AgentNet Browser Extension

### 1. Download and unzip the browser extension: [**Link**](https://drive.google.com/drive/folders/14EJGi6buBT5O4mJ-58ghMkaZf1uXS1oN)

### 2. Install the extension in your browser

Take **Google Chrome** as an example:

#### 2.1 Click "Customize and Control Google Chrome" -> "Extensions" -> "Manage Extensions"

#### 2.2 Turn on **Developer mode**, click **Load unpacked**

#### 2.3 Enter the unzipped folder "htmlsniffer" then select the htmlsniffer folder inside.

#### 2.4 Then you will see the extension loaded in your browser!

<div class="image-collection">
    <div class="image-container">
        <img src="../windows_assets/html0.png" alt="img" class="step-image">
        <div class="step-tag">2.1</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/developer_mode.png" alt="img" class="step-image">
        <div class="step-tag">2.2</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/html2.png" alt="img" class="step-image">
        <div class="step-tag">2.3</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/html3.png" alt="img" class="step-image">
        <div class="step-tag">2.4</div>
    </div>
</div>

## Step 3 Download and Setup AgentNet Tool

### 1. Download and unzip the app from [**Link**](https://drive.google.com/drive/folders/1ycugrYPh8M2Bu6hlt1-3rZrOIxQLtseu)

#### 1.1 Click **agentnet-annotator.exe** in the folder to open AgentNet Tool

#### 1.2 Note: If you click the .exe file but the window didn't show up, please check your [OBS setting](#step-1-obs-setup). Make sure your OBS is the right version and everything is correctly set up.

<!-- The App's home page looks like below.

<div style="text-align: center;">
    <img src="../windows_assets/app1.png" alt="img" style="zoom:33%; width: 75%;">
</div> -->

### 2. Enable Privacy & Security Permissions

#### 2.1 If you encounter alert from Microsoft Defender SmartScreen, click "more information", then click "Run anyway".

#### 2.2 If you see the Windows Safety Center alert, click "Allow" for backend.exe.

#### 2.3 After logging in using Google Account (or Prolific account), you can see the start recording page in "Home":

<div class="image-collection">
    <div class="image-container">
        <img src="../windows_assets/AD_4nXdILQ4EVsS6AJ_0C1Nk5bqSlJQgJWEV2Ax4OyzJM7lyznGZ_xob-N_LZFfQT3-JkBKvO16UbS2C9LkzAVqoDn9W7_V2hYwO0ZsOLXx5CBRa4OWyTzMpSVAdvx7AIfRcxutdlB27GG6tYBQsi8M1gVanYkVf.png" alt="img" class="step-image" />
        <div class="step-tag">2.1</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/AD_4nXeUI3Y5EtR6WTpOj_Pl2jSg6EdlclUw_zBcbBUX6lIgtdnojywZvTA-zYT3taaC1KWC1F-FqqV4_wYI6_nq83WG62J6hSmNy-a3x370JP-1WVQtV84opr3_fxZj-tjACaihYB1yOCKrZHERN8IITYuVmB8H.png" alt="img" class="step-image" />
        <div class="step-tag">2.2</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/app1.png" alt="img" class="step-image"/>
        <div class="step-tag">2.3</div>
    </div>
</div>

### 3. A Common Issue

You may meet this bug if you install OBS and the app for the first time

When you click "Start Recording", the OBS doesn't start to record (OBS Icon didn't turn red).

<img src="../windows_assets/obs_icon1.png" style="zoom:70%;" />

Click the OBS, this bug shows:

<img src="../windows_assets/bug.png" style="zoom:50%;" />

No worry, this is because our app needs to set up OBS for the first time. You should **close the app and the OBS**, open the app again, then click start recording. You will be able to see the OBS Icon turns red, meaning recording started.

<img src="../windows_assets/obs_icon.png" style="zoom:70%;" />

Here is a video about how to solve this bug.

<video width="500" controls>
  <source src="../windows_assets/obs_start_bug.mp4" type="video/mp4">
</video>
