---
layout: default
title: Troubleshooting
nav_order: 6
---

# Troubleshooting
{: .fs-9 }
{: .no_toc}
{: .fs-6 .fw-300 }

---

## TABLE OF CONTENTS
{: .no_toc .text-delta}
1. TOC
{:toc}

---

# Python Not Working in Your Command Prompt

If your Python is not on your **PATH**, your Python will not be working in your Command Prompt.

You **MUST** place your Python program on your **PATH**.

Let's do it!!

1. Search for **python.exe** using Windows search like figure below. Then, right-click the search result, and click *Open file location*.

    ![Find-Python](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/find_python.png?raw=true "Find Python")

2. Right click the address bar in the File Explorer, and click *Copy address as text* as figure below.

    ![Copy-address](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/copy_address_as_text.png?raw=true "Copy address")

3. Click Windows search again, search for **Control Panel**, and open Control Panel.

    ![Opening-control-panel](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/opening_control_panel.png?raw=true "Opening control panel")

4. Type **environment** in the search bar on the top right of Control Panel. Then, click *Edit environment variables for your account*.

    ![Search-environment-in-control-panel](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/search_environment_in_control_panel.png?raw=true "Search environment in control panel")


5. Move your cursor to *Path* in the **Environment Variables window**. Then, click *Edit...* button.

    **CAUTION**
      {: .label .label-yellow }
          DO NOT get confused with Path in System variables (at the bottom).
          You MUST choose Path in User variable (at the top).

    ![Changing-path-1](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path.png?raw=true "Changing path 1")

6. Click *New* button and type the address that you copied from step 2. Click *New* button again, type the address again, and add **Scripts\\** at the end. Click *OK* when you are done with adding two paths.

    ![Changing-path-2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path_2.png?raw=true "Changing path 2")

7. Click *OK* again. Then, you will have successfully added your Python on **PATH**.

    ![Changing-path-3](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/changing_path_3.png?raw=true "Changing path 3")

---

# Cannot Directly Log-in to GitHub Account.
If you are unable to log-in with your GitHub account credentials. [Try logging-in with a personal access token.](./ui-components/ui-components.md#option-b---log-in-with-personal-access-token)

---
