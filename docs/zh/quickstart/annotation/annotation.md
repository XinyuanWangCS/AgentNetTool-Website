# Annotation Guidance

!!! Warning "Security&Privacy"

    For tasks that you choose not to upload, only you can see them. But your uploaded recorded video can be viewed by the developer and others, please ensure that the content you upload does not contain any private or sensitive information.

## Annotation Pipeline

!!! Note

    The following steps outline the process of an annotation.

### 1. Log in to AgentNet Using Your Google Account (or Prolific Account)

We aim to track each user's recordings and perform the corresponding verification, so logging into AgentNet is a necessary prerequisite for starting the application.

### 2. Open & Setup OBS Before Recording

You need to open and setup OBS before using AgentNet to record your task.

### 3. Start Recording

<img src="../assets/1.png" style="zoom:25%;" />

After logging and setting up OBS, you may click "Start Recording" or use the shortcut "Control + Alt + R" to start a record.

### 4. Perform your task on your PC:
- You can operate your PC as normal (click, type, drag, scroll...), AgentNet is recording in the background

<img src="../assets/operate computer.png" style="zoom:21%;" />

### 5. Stop Recording:

Conclude the recording once the task is completed: Use the combination key "Ctrl+Shift+T" or open the app and Click "Stop Recording".

<img src="../assets/stop_recording.png" style="zoom:33%;" />

### 6. Review Recorded actions:
- The task you have just done is named in the format of "recording-datetime", and it will be list below the "Local" in the sidebar.
- AgentNet will need some time to process the new recording, you would have to wait 10s for a short task (1~2 mins), or longer for a long recording (few minutes for a more than 20-minute long task), but you can do other tasks during this processing time.

<img src="../assets/new_record_sidebar.png" style="zoom:21%;" />

We can see the task name is "recording-20240903_102300(untitled)" and the task description is "...(No description provided. Please add details here)", which we need to annotate later. There are in total 43 actions that were saved, each of which has a video clip on the left and action name & description on the right. Some of the actions aren't necessary and can be removed. 

<img src="../assets/first_action.png" style="zoom:21%;" />

#### 6.1 Delete Redundant Actions
 -By clicking the delete sign on the top-right of the selected action, you can delete one action.

<img src="../assets/delete.png" style="zoom:50%;" />

- One rule to decide whether to delete or keep an action: If you do this task again, without one action, you won't be able to successfully finish the task, then keep it, otherwise delete it. After deleting the redundant actions, all the actions left are key actions.

- Here are some examples in the task "Set up Zoom meeting with JL on Sunday" about which action to keep and which to delete:

  - Irrelevant Action: Action 5 clicking space, which is a redundant movement, has no actual meaning, should be deleted.

  <img src="../assets/AD_4nXc6fm-_ZSlRecodpRIhbKMnej_gKh_Ji2mIpetvXyFZ_5AyRWjnGvTcQnRZ_9e4pVstMw7frrIByaf9AKHTaSD2t_AtwOLs5ZaVqV_bp5Fe9HG67vKscf7O1SQSYzQ7U341B7tiaWaAnIPvKXyg2yzwerRN.png" style="zoom:33%;" />
  
  - Unnecessary Actions: Action 11, click Windows Calendar is not necessary for the task, because Zoom has already provided calendar when picking the date. Without this action, we can still successfully replay the whole task.

  <img src="../assets/click_calendar.png" style="zoom:22%;" />
  
  <img src="../assets/zoom_calendar.png" style="zoom:50%;" />

  - Off-Task Actions:  Opening a Google Doc has nothing to do with my task "setting up Zoom meeting", so it should be removed. Actions are not related to the task objective can be removed. 

  <img src="../assets/AD_4nXcJYgrAf3zIUi9itJU7p3_ZYVLgdFBUqvQoSgrVib8fG2i0eSGd_tSbaGKm5Zm-NBpw3CPtjUp62b0bc73jfvkVKosWiDr1TZTYPhyPkQJaB-Of6f5q2X2Uib6wGz7mnO7GuGgpazM4Py_ByO_NZrU5ZMSB.png" style="zoom:33%;" />

  
  - Essential Actions: Clicking "Schedule", Enter meeting name, and Picking meeting date are crucial for task completion, must be retained.

  <img src="../assets/click_schedule.png" style="zoom:21%;" />
  <img src="../assets/type_meeting_name.png" style="zoom:21%;" />
  <img src="../assets/pick_date.png" style="zoom:21%;" />
  

#### 6.2. Editing Action Details:

- By double-click the Action title or description, you can edit this action. For click actions, we should describe the acutal button we clicked. For example, change "Click" to "Click Schedule"

<img src="../assets/edit.png" style="zoom:22%;" />

<img src="../assets/edit1.png" style="zoom:50%;" />

- After all the edition, the action list should look like this:

<img src="../assets/final_edit.png" style="zoom:22%;" />

### 7 Annotate task name and Description

- Click "Annotate" and Enter Task name and Description
- Task name: one or a few concise sentences that summarize the goal of the task.
- Description: Step-by-step describing how to perform the task.

<img src="../assets/annotate.png" style="zoom:22%;" />

#### 7.1 Polish by AI
- After entering the task name and description, you can click "Polish by AI" and AI will help you correct the grammar and format the description.
- Note: please review the polished text and make sure it's correct before save.

<img src="../assets/polish.png" style="zoom:22%;" />

#### 7.2 Create a sub-task
- If you record many tasks in one recording, you can select the First and Last action, enter it's task name and description, then click "Save". Then this sub-task will be saved independently, you can check it on the sidebar.

<img src="../assets/cut.png" style="zoom:50%;" />

### 8. Upload Annotations:

- Upload: To finalize and submit the annotation, click the 'upload' button. Please upload the task data once it is completely processed


