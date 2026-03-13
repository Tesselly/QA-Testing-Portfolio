# Web Application Testing – TodoMVC

## Test Case 1: Add a new task

Test Case ID: WEB_TC_01

Steps:
1. Navigate to the TodoMVC application
2. Type "Buy milk" in the input field
3. Press Enter

Expected Result:
A new task should appear in the list.


## Test Case 2: Add multiple tasks

Test Case ID: WEB_TC_02

Steps:
1. Add a task "Buy milk"
2. Add a second task "Finish testing portfolio"

Expected Result:
Both tasks should appear in the task list.


## Test Case 3: Mark task as completed

Test Case ID: WEB_TC_03

Steps:
1. Add a task
2. Click the checkbox beside the task

Expected Result:
The task should be marked as completed.


## Test Case 4: Delete a task

Test Case ID: WEB_TC_04

Steps:
1. Add a task
2. Hover over the task
3. Click the delete (X) button

Expected Result:
The task should be removed from the list.


## Test Case 5: Filter tasks

Test Case ID: WEB_TC_05

Steps:
1. Add multiple tasks
2. Mark one as completed
3. Click "Active"
4. Click "Completed"

Expected Result:
Active filter shows active tasks only.
Completed filter shows completed tasks only.
