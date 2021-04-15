---
layout: default
title: Setting Up PyCharm
nav_order: 2
permalink: /docs/configuration
---

# Setting Up PyCharm
{: .no_toc }


Before writing actual code with PyCharm, you need to make a basic setup for PyCharm.
You will be able to create a new project in your PyCharm and Python file by successfully follow the steps below.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Check if Python is Working
If you successfully installed Python, Git, and PyCharm, the first thing you need to do is to check if your Python program is working.

In Windows 10, you can check it using Command Prompt.

1. Press ***WIN*** ( ![windows-key](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/windows_logo.png?raw=true "windows key") ) + ***R***.

2. Type **cmd** in the Run window and press *OK* as the figure below shows.

    ![cmd-run](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/run_cmd.png?raw=true "Run cmd")
    
    If you were able to open Command Prompt, the next step is to execute the Python in it.

3. Type **python** in your Command Prompt like below (<span style="color:red">**CASE INSENSITIVE**</span>).

    ![cmd-python-implementation](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/1.cmd_python_implementation.png?raw=true "Python implementation in cmd")
    
    If it is successful, you can see the current version of your Python, and after that, you will see three close angled brackets(```>>>```).
    
    The brackets indicate that you are currently using the Python interpreter.

    ![cmd-python-implementation2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/2.cmd_python_implementation_2.png?raw=true "Python implementation in cmd")
    
    **STOP**
    {: .label .label-red }
        If you failed to execute Python program in your Command Prompt, you MUST add Python to Windows PATH.
        To add Python to Windows PATH, please click the following link.
    
    [Troubleshooting - Python Not Working in Your Command Prompt](https://sis00337.github.io/Pycharm-For-Dummies/docs/index-test/#python-not-working-in-your-command-prompt)
    
    
    Next, let's print **Hello World** using Python.

4. Type **print("Hello World")** next to the angled brackets and press *ENTER* (<span style="color:red">**CASE SENSITIVE**</span>).

    You will see **Hello World** is printed on your screen.

    ![cmd-hello-world](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/3.cmd_hello_world.png?raw=true "Print hello world in cmd")

    **GO**
    {: .label .label-green }
        If you successfully followed the steps all the way here, it means your Python is perfectly working.

5. Type **quit()** to terminate Python in your Command Prompt.

    ![cmd-quit](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/4.cmd_quit().png?raw=true "Quit Python from cmd")

Great! Your Python seems to be working perfectly!

Next, let's create a new project in PyCharm.

---

## Create a New Project in PyCharm
In this stage, you will be able to create a new project in your PyCharm.

1. Open your PyCharm and click the *New Project* button.

    ![PyCharm-starting-page](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/5.PyCharm_Starting_Page.png?raw=true "PyCharm starting page")

2. Click the arrow as is shown in the first red box and click the *etc* button (```...```) as the second red box shows.
    
    **GO**
    {: .label .label-green }
        If you can see an interpreter as the figure below, GO STRAIGHT TO STEP 5.
    
    ![Creating-new-project-1](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/7.click_down_arrow.png?raw=true "Creating new project")

3. Select *System Interpreter* from the left navigation bar and click the *etc* button (```...```).

    Then, find the path to *python.exe* file. It is usually in **C:\Users\\\[YOUR_USER_NAME\]\AppData\Local\Programs\Python\Python38\python.exe**.

    **CAUTION**
    {: .label .label-yellow }
        The number with Python (e.g., Python38) may vary depending on the Python version you installed.

    When you have found your *python.exe* file, click the *OK* button.

    ![Creating-new-project-2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/8.find_interpreter.png?raw=true "Creating new project 2")

4. Double check that you can see the interpreter correctly and press the *OK* button.

    ![Creating-new-project-3](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/9.Interpreter_found.png?raw=true "Creating new project 3")

5. Press the *Create* button, then you get a new project in your PyCharm.

    ![Creating-new-project-4](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/10.create_new_project.png?raw=true "Creating new project 4")
    
    After you create a new project, you will see a window like the figure below.

    ![Creating-py-file-1](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/11.first_window_after_creating_project.png?raw=true "Createing py file 1")

Fantastic! You successfully created a new project in your PyCharm!

Next, let's create a **.py** file in your project.

---

## Create **.py** File into the Project
You will be able to create a **.py** file after completing the following steps.

1. Right-click the project directory, hover on **New** and click **Python File** sequentially.

    ![Creating-py-file-2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/12.create_new_python_file.png?raw=true "Createing py file 2")

2. Name your new **.py** file (HelloWorld in this example) and press *ENTER*.

    ![Creating-py-file-3](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/13.creating_py_file.png?raw=true "Createing py file 3")
    
Brilliant! You successfully created a **.py** file in your project!

You can also create multiple **.py** files in a project by repeating the steps above.

Finally, let's run the **.py** file!

---

## Run Your **.py** File
Running your **.py** file is one of the fundamental practices for Python beginners because you can check if your codes are working by running the codes.

You will be able to learn how to run a **.py** file by following the steps below.

1. Type your Python code like **print("Hello World")**, right-click on your screen, and click *Run \[YOUR_FILE_NAME\]*

    ![Run-your-py-file-1](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/14.run_py_file.png?raw=true "Run your py file 1")

2. Check the result of the execution.

    ![Run-your-py-file-2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/15.after_run.png?raw=true "Run your py file 2")

Congratulations!!! You successfully finished setting up your PyCharm.

Next, try to follow [Linking to GitHub](https://sis00337.github.io/Pycharm-For-Dummies/docs/ui-components) if you want to use PyCharm more efficiently.
