<link rel="stylesheet" href="../assets/style.css">
# MacOS

## Installation Overview

To use our AgentNet annotation tool, you have to install and setup the following **3** tools:

1. **OBS** is used for recording your desktop screen.
2. **Browser Extension** is used for obtaining the webpage html data.
3. **AgentNet** is a our annotation app that uses OBS to record your desktop and browser extension to get the webpage html data.

## Step 1: OBS Setup

### 1. Download & Installation

#### 1.1. Download OBS from [OBS Official Website](https://obsproject.com/).

#### 1.2 Run the installer and grant OBS the necessary permissions for installation.

#### 1.3 Choose **Optimize just for recording**

#### 1.4 Click **Next** for video setting

#### 1.5 Click **Apply Settings**

<div class="image-collection">
    <div class="image-container">
        <img src="../mac_assets/obs_permission.png" alt="img" class="step-image" />
        <div class="step-tag">1.2</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/obs_optimize.png" alt="img" class="step-image" />
        <div class="step-tag">1.3</div>
    </div>
        <div class="image-container">
        <img src="../mac_assets/obs_video_setting.png" alt="img" class="step-image" />
        <div class="step-tag">1.4</div>
    </div>
        <div class="image-container">
        <img src="../mac_assets/obs_apply_settings.png" alt="img" class="step-image" />
        <div class="step-tag">1.5</div>
    </div>
</div>

### 2. Setup OBS

#### 2.1 Back on the home page of OBS, select **"Scene"** Under "Sources", click the **"+"** button and then click **Deprecated -> Display Capture**.

#### 2.2 Make sure the "Display" is set to your main display, and you should see your screen on the canvas:

<div class="image-collection">
    <div class="image-container">
        <img src="../mac_assets/obs_display_capture.png" alt="img" class="step-image" />
        <div class="step-tag">2.1</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/full_screen.png" alt="img" class="step-image" />
        <div class="step-tag">2.2</div>
    </div>
</div>

### 3. Allow full disk access

<img src="../mac_assets/fulldisk_obs.png" style="zoom:33%; width: 50%;" />

### 4. OBS setup tutorial video (Optional)

Here's a tutorial video for all the steps mentioned. **Skip** if you've already followed the instructions.

<iframe width="560" height="315" src="https://www.youtube.com/embed/u_okvcFomd0?si=7GYawr_KNn3uRkGC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Step 2 Install AgentNet Browser Extension

### 1. Download and unzip the browser extension: [**Link**](https://drive.google.com/drive/folders/14EJGi6buBT5O4mJ-58ghMkaZf1uXS1oN)

### 2. Install the extension in your browser

Take **Google Chrome** as an example:

#### 2.1 Click "Customize and Control Googl Chrome" -> "Extensions" -> "Manage Extensions"

#### 2.2 Turn on **Developer mode**, click **Load unpacked**

#### 2.3 Enter the unzipped folder "htmlsniffer" then select the htmlsniffer folder inside.

#### 2.4 Then you will see the extension loaded in your browser!

<div class="image-collection">
    <div class="image-container">
        <img src="../mac_assets/image-20240903031632853.png" alt="img" class="step-image" />
        <div class="step-tag">2.1</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/image-20240903031736815.png" alt="img" class="step-image" />
        <div class="step-tag">2.2</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/image-20240903031821225.png" alt="img" class="step-image" />
        <div class="step-tag">2.3</div>
    </div>
    <div class="image-container">
        <img src="../windows_assets/html3.png" alt="img" class="step-image" />
        <div class="step-tag">2.4</div>
    </div>
</div>

<!-- #TODO -->

<!-- ### 3. Extension configure tutorial (Optional)

Here's a tutorial video for all the steps mentioned. **Skip** if you've already followed the instructions.

<iframe width="560" height="315" src="https://www.youtube.com/embed/GQwyRPew8Io?si=T_4UE9XlJ4UT7wKu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>
</iframe> -->

## Step 3 Download and Setup AgentNet Tool

Please download from this [**Link**](https://drive.google.com/drive/folders/1fplOrubnxyPh2y71HXrT8940carHSjsq) and double click on the .dmg file to install the AgentNet tool.

### 1. OBS auto configuration through AgentNet Tool

#### 1.1 Ope the AgentNet Tool, click OBS Configure

#### 1.2 Restart OBS

<!-- #TODO -->

<div class="image-collection">
<div class="image-container">
<img src="../mac_assets/annotator_obs_config.png" class="step-image" />
<div class="step-tag">1.1</div>
</div>
</div>

### 2. Permissions and security settings

#### 2.1 Input Monitoring

#### 2.2 Accessibility

#### 2.3 Notification: Please enable 'Allow Notifications when mirroring or sharing the display.'

<div class="image-collection">
    <div class="image-container">
        <img src="../mac_assets/input_monitor.png" alt="img" class="step-image" />
        <div class="step-tag">2.1</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/accessibility.png" alt="img" class="step-image" />
        <div class="step-tag">2.2</div>
    </div>
    <div class="image-container">
        <img src="../mac_assets/notifications.png" alt="img" class="step-image" />
        <div class="step-tag">2.3</div>
    </div>
</div>

## Step 4 Setup iBar (Optional)

Please start AgentNet annotator app. If you can see the AgentNet icon in your computer's menu as the picture below, you can skip the below.
<img src="../mac_assets/agentnet_ibar_shown.png" style="zoom:33%;"/>

if you can't see AgentNet on your computer's menu, please: 1) Download iBar [here](https://www.better365.cn/ibar.html) 2) Setup your iBar as below 3) Uncheck AgentNet 4) Make sure you can see AgentNet icon in your menu

<div class="image-collection">
<div class="image-container">
<img src="../mac_assets/ibar_general.png" alt="img" class="step-image" />
<div class="step-tag">2</div>
</div>
<div class="image-container">
<img src="../mac_assets/ibar_uncheck.png" alt="img" class="step-image" />
<div class="step-tag">3</div>
</div>
<div class="image-container">
<img src="../mac_assets/ibar_menu.png" alt="img"  />
<div class="step-tag">4</div>
</div>
</div>
