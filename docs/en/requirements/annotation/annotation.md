<link rel="stylesheet" href="../assets/style.css">
# Annotation Pipeline

???+ Warning "Make sure installation and stetup has been complete"
    Before reading the section below, make sure you have completed every step in the installaton section for [Windows](../../../quickstart/windows_quick_start.md) and [MacOS](../../../quickstart/mac_quick_start.md)

## Annotation Pipeline Overview

Annotation Pipeline contains **5** steps:

- **Step 1: Open OBS and login AgentNet**
- **Step 2: Record a task using AgentNet tool**
- **Step 3: Review the recorded task**
- **Step 4: Write task description**
- **Step 5: Upload the task <span style="color:red;">(we cannot see your annotated task until it's uploaded)</span>**
<!-- - **Step 5: Check your uploaded task status** -->

!!! Warning "Privacy"
    AgentNet Tool will capture your screen, mouse and keyboard activities, including browser and app content. You can annotate any computer tasks, but ensure that you only upload those without any personal data you prefer not to share. Your data cannot be previewed until it is uploaded. You can review our [**consent form**](https://docs.google.com/document/d/1U4SboHN9MJ1zlohj8yI31lIdJmZkFDUbzgOM126vl5w/edit?usp=sharing) for more details.

## Step 1: Open OBS and Login AgentNet

#### 1.1 Open OBS and AgentNet Tool

#### 1.2 Login to AgentNet using Google Account or provided login code

#### 1.3 Check the OBS and AgentNet icon: If AgentNet icon is hidden, please [move it to the visible place](https://zeonlap.github.io/agentnet-docs/quickstart/mac_quick_start/#step-4-setup-ibar-optional).

<div style="text-align: center;">
    <img src="../assets/ano8.png" alt="img" style="zoom:33%;">
</div>

## Step 2: Record a Task using AgentNet Tool

#### **2.1 Start Recording**: Whenever you have a task in mind (e.g. "Schedule a Zoom meeting with Junlin for next Monday"), click "**Start Recording**" and the AgentNet app window will be minimized automatically.

#### **2.2. Demonstrate the task**: You can operate your PC as normal (click, type, drag, scroll...) to complete the task, **please <span style="color:red;">avoid any unnecessary or irrelevant actions that are not related to the task</span>**.

#### **2.3. Stop Recording**: You can open the app and **click "Stop Recording"** once you finish the task, or use the hotkey "Ctrl+Shift+T" (Windows) / "Cmd+Option+T" (MacOS).

In the example task, the actions are: Open Schedule meeting in Zoom; Set up meeting time and participants; Create Google Calendar event.

<div style="text-align: center;">
    <img src="../assets/ano12.png" alt="img" style="zoom:33%;">
</div>

- <span style="color:red;">**Pay Attention**</span>: The AgentNet will capture computer data during recording. Please don't move (click/type) when the icon is red (we are fetching the data at the moment)! Otherwise the collected task data will be incomplete!

<div style="text-align: center;">
    <img src="../assets/ano10.png" alt="img" style="zoom:33%;">
</div>

## Step 3: Review the Recorded Task


After processing, new recording will be generated below the "Local" sidebar, clicking on the recording to see the **recorded task** as shown below.

<div style="text-align: center;">
    <img src="../assets/ano13.png" alt="img" style="zoom:33%;">
</div>

Review all captured actions on the right panel to ensure:

 1. **Action match**: Verify that the action in the video clip matches the corresponding action in the action list (Blue arrow in the above screenshot).
 2. **Unnecessary actions**: Delete redundant actions and keep only those essential for the task. Follow this **Basic Rule**: If the task cannot be completed without an action when repeated, keep it; otherwise, delete it.



<!-- 
### **3.1 Check action correctness**

We summarize and visualize your actions into the following **6 action types**. Please check:

#### 1. **Action match**: The action name and video match your actual action.

#### 2. **Mouse position match**: The red circle in **Click** shows the actual position you clicked.

<div style="text-align: center;">
    <img src="../assets/ano15.png" style="zoom:30%;" />
</div>

<div style="text-align: center;">
    <img src="../assets/ano16.png" style="zoom:30%;" />
</div> -->

<!-- ### **3.2 Delete Unecessary Actions**

We only need the actions related to the task, so any redundant actions should be deleted.

<span style="color:red;">**Basic Rule**</span>: **If you do this task again, you can't complete the task without this action, then keep the action. Otherwise, delete it**.

There are some examples of deleted actions in the example **Schedule a Zoom meeting with Junlin for next Monday**.

???+ Failure "Redundant Action"
    Action 5 is clicking space, which has no actual meaning, should be deleted.

    <div style="text-align: center;">
    <img src="../assets/AD_4nXc6fm-_ZSlRecodpRIhbKMnej_gKh_Ji2mIpetvXyFZ_5AyRWjnGvTcQnRZ_9e4pVstMw7frrIByaf9AKHTaSD2t_AtwOLs5ZaVqV_bp5Fe9HG67vKscf7O1SQSYzQ7U341B7tiaWaAnIPvKXyg2yzwerRN.png" style="zoom:33%;" />
    </div>

???+ Failure "Actions that is not related to the task"
    Clicking "Share Screen" is not related to schedule a Zoom meeting.

    <div style="text-align: center;">
    <img src="../assets/ano17.png" style="zoom:22%;" />
    </div> -->

<!-- ### **3.3 Check video and screen mismatch (if applicable)**

If the recording only captures part of your screen, reconfigure OBS Display Capture to ensure it captures the entire screen.

<div style="text-align: center;">
    <img src="../assets/ano14.png" style="zoom:25%;" />
</div>
-->
## Step 4: Write Task Description

After reviewing the recorded task, you need to click on **"Annotate"** button first, and then write down the natural language description of the task in the **"Task name"** field.


<div style="text-align: center;">
    <img src="../assets/app12.png" style="zoom:30%;" />
</div>

<span style="color:red;">**Basic Rule**</span>: **Ensure that others can understand and replicate the task by reading the task description. Strive for a balance between being too abstract and overly specific.**

Examples of good and bad task descriptions are provided to illustrate our expectations.

???+ Tip "Good Examples"
    **1. How can I display all attendees' videos at an equal size on Zoom?**

    **2. Use Zoom to schedule a meeting with the XLANG team for the project update. Send the meeting invite to all team members by email**

    **3. Create a sales report using Excel that includes data for Q1. Share the report with the sales manager via Google Drive.**

    **4. Log in to WordPress and update the homepage banner to reflect the new promotion. Ensure to save changes and preview before publishing.**

???+ Tip "Bad Examples"
    **1. Schedule a meeting and send it through email.** (<span style="color:red;">Vague about which platform to use and who the email should go to.</span>)

    **2. Open Spotify and listen to the first song of my favourite singer.** (<span style="color:red;">Too personal; it doesn't specify which song or how to find it.</span>)

    **3. Make some changes to the website.** (<span style="color:red;">Too ambiguous; doesn't specify what website and what changes</span>)

    **4. Click on the website, click the project section, and change the text to "New Launch", take a screenshot, add the picture to the end.** (<span style="color:red;">Overly detailed</span>)

    

??? Tip "Polish by AI (Advanced feature, not recommended)" 
    - We provide a feature using AI to help you correct the grammar and format. 
    - Note: Please only use it when you feel there are many grammar errors. We need natural task desciptions in general, not all generated by AI. You should **review the polished text** and make sure it's correct before save.
    <div style="text-align: center;">
    <img src="../assets/app13.png" alt="img" style="zoom:22%;">
    </div>

??? Tip "Create a sub-task (Advance feature)"
    - If you record many different tasks in one recording, you can select the **First** and **Last** action, enter it's task description, then click "Save". Then this sub-task will be saved independently, you can check the new saved task from the sidebar.
    <div style="text-align: center;">
        <img src="../assets/app14.png" alt="img" style="zoom:22%;">
    </div>

## **Step 5: Upload the Task**

<span style="color:red;">**We cannot see your annotated task until it's uploaded. Please make sure to upload it after finished**</span> by clicking "**upload**"!

<img src="../assets/app15.png" alt="img" style="zoom:22%;">



## Annotation Pipeline Tutorial Video (Optional)

Here's a tutorial video that walks through recording, reviewing and uploading steps mentioned above. **Skip** if you've already understood the instructions.

<!-- #### Example 1: Check Google Calendar, find the currently happening event, enter the Zoom meeting, check the participants. -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/8yssjkSOMUE?si=2ormJQaPW-omeoLn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!-- #### Example 2: Follow the slides, test the 'sapply' function on 'csn', test the 'sqrt' function, and test 'plot' with 'csn' and 'sqrt'

<iframe width="560" height="315" src="https://www.youtube.com/embed/71AjmL1gcPY?si=iX4TMo_e-tpER1NR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe> -->
