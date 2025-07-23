# Good annotated task examples

## Annotated tasks from a high-quality annoator should have:
- Diversity: Tasks are from different domains, using different apps/website, doing different kinds of tasks.
- Complex: Each task should have a relatively long trajectory.
- Good task name and description: Task name and task description are detailed and correct.
- Accurate and polished actions: Actions are correct, pruned and action names are polished.

???+ Success "Example task 1: Create a VPC named 'my-test-vpc' with its subnet and internet gateway."

    ### Description: 
    - Step 0: Access the AWS Management Console. Step 1: Navigate to the VPC section. Step 2: Create the VPC by setting the name to 'my-test-vpc' and specifying the CIDR block. Step 3: Create a subnet by selecting the newly created VPC, setting the subnet name, CIDR block, and availability zone. Step 4: Create an internet gateway, set the name, and attach it to the VPC.

    - Step 0: Access the AWS Management Console. (Action 1~4)

    <img src="../assets/t1.png" style="zoom: 30%;" />

    <img src="../assets/t5.png" style="zoom: 30%;" />

    Step 1: Navigate to the VPC section. (Action 4~7)

    <img src="../assets/t2.png" style="zoom: 30%;" />

    <img src="../assets/t6.png" style="zoom: 30%;" />

    Step 2: Create the VPC by setting the name to 'my-test-vpc' and specifying the CIDR block. (Action 8~16)

    <img src="../assets/t9.png" style="zoom: 30%;" />

    Step 3: Create a subnet by selecting the newly created VPC, setting the subnet name, CIDR block, and availability zone.

    <img src="../assets/t8.png" style="zoom: 30%;" />

    <img src="../assets/t3.png" style="zoom: 30%;" />


    Step 4: Create an internet gateway, set the name, and attach it to the VPC. (Action 29~41)

    <img src="../assets/t7.png" style="zoom: 30%;" />

    ### Review the task
    - Good task name and description: The task name accurately summarized the goal of the task. The description shows the step-wise plan to finish the task.

    - Diversity: This task is a professional task on AWS EC2, which is not commonly used by regular PC users.

    - Accurate and polished actions: Every action is checked. Most of the click are manually modified and grounded to the real button on the website. Redundant actions are removed. There is no missing or error actions.

    - Complex: This task requires professional knowledge of AWS. This task has 41 actions in the trajectory










