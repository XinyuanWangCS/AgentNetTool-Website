<link rel="stylesheet" href="../assets/style.css">

# Ubuntu

!!! warning 
    To support OBS versions above 28, we recommend that users on **Ubuntu 24.04 or later** use the AgentNet Tool for the simplest OBS installation.

## Installation Overview

To use our AgentNet annotation tool, you have to install and setup the following **2** tools:

1. **OBS** is used for recording your desktop screen.
2. **AgentNet Tool** is a our annotation app that uses OBS to record your desktop and browser extension to get the webpage html data. **We recommend that Ubuntu users start the application using our code repository with `npm start`**.

We also provide an optional browser extension to help you annotate the webpage html data.

# Step 1 OBS Setup

### 1. Download & Installation

#### 1.1 Download **latest version** of OBS from following [OBS Download Link](https://obsproject.com/download) (Choose Linux).

Typically, you can download OBS using the following command:

```bash
sudo add-apt-repository ppa:obsproject/obs-studio
sudo apt update
sudo apt install obs-studio
```

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

### 5. Change Output Mode to Advanced (Optional)

If your Ubuntu system can’t start recording properly, you can try setting the Output Mode to Advanced, as shown below.

<div class="image-collection">
    <div class="image-container">
        <img src="../ubuntu_assets/obs_output_1.png" alt="img" class="step-image">
        <div class="step-tag">5.1</div>
    </div>
    <div class="image-container">
        <img src="../ubuntu_assets/obs_output_2.png" alt="img" class="step-image">
        <div class="step-tag">5.2</div>
    </div>
</div>

## Step 2 Download and Setup AgentNet Tool

### 1. Clone the code repository and follow the instructions in the README.md file to install the dependencies.

Typically, you can install the dependencies using the following command:

```bash
pip install -r requirements_ubuntu.txt
cd agentnet-annotator
npm install
```

We recommend you use python==3.12 and node>=v24 to run the tool.

### 2. Start the AgentNet Tool by running `npm start`.
