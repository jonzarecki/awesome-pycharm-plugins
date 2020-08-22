# Awesome PyCharm Plugins [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome PyCharm plugins.
List of all plugins can be found in [here](https://plugins.jetbrains.com/pycharm).

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- Tools integration
    - [BlackConnect](#blackconnect)
    - [Data Version Control (DVC) Support](#data-version-control-dvc-support)
    - [Gitlab Integrations](#gitlab-integrations)
    - [Jira Integration](#jira-integration)
    - [Big Data Tools](#big-data-tools)
    - [Jenkins Control Plugin](#jenkins-control-plugin)
- Code Tools
    - [Save Actions](#save-actions)
    - [Python Annotations](#python-annotations)
    - [SonarLint](#sonarlint)
    - [Pylint](#pylint)
    - [Code Cleaner with Code Climate CL](#code-cleaner-with-code-climate-cl)
- Apps, Notification and Interaction Applications
    - [Key Promoter X](#key-promoter-x)    
- User Interface
    - [CPU Usage Indicator](#cpu-usage-indicator)
    - [GPU Monitor](#gpu-monitor)
    - [Rainbow Brackets](#rainbow-brackets)
    - [Extra Icons](#extra-icons)
- [Themes](#themes)
- Fun stuff
    - [Power Mode II](#power-mode-ii)
    - [Progress Bars](#progress-bars)
- Version Control
    - [.ignore](#ignore)
    - [Conventional Commit](#conventional-commit)
- Editor
    - [Quick File Preview](#quick-file-preview)
    - [Python custom import](#python-custom-import)   
- Languages
    - [CSV Plugin](#csv-plugin)    
    - [BashSupport](#bashsupport)      
- Spellcheck
    - [Grazie](#grazie)     
- PDF
    - [PDF Viewer](#pdf-viewer)
- Reporting
    - [WakaTime](#wakatime)
- Viewer
    - [OpenCV Image Viewer](#opencv-image-viewer)
- Miscellaneous
    - [Archive browser](#archive-browser)
    - [Dictionary](#dictionary)
    - [PyCharm Help](#pycharm-help)    
- Code Editing
    - [Emoji Support Plugin](#emoji-support-plugin)
                       
- [Contributing](#contributing)

- - -

# [Tools integration](https://plugins.jetbrains.com/tag/19-tools-integration)

## BlackConnect

[Kirill Borisov](https://github.com/lensvol/) 

- 2+ Ratings. 4.4 out of 5
- 1000+ Downloads
- Jul 25, 2020

Connect to [blackd](https://black.readthedocs.io/en/stable/blackd.html) and format your Python code without creating a new **black** process!

![image alt text](media/blackconnect.png)

Pretty good. Can work in addition to Save Actions.

[https://plugins.jetbrains.com/plugin/14321-blackconnect](https://plugins.jetbrains.com/plugin/14321-blackconnect)

## Data Version Control (DVC) Support

[David Příhoda](http://dvc.org/) 

- 1+ Rating. 4.5 out of 5
- 1,500+ Downloads
- Feb 03, 2019

Data Version Control (DVC) file support.

[https://plugins.jetbrains.com/plugin/11368-data-version-control-dvc-support](https://plugins.jetbrains.com/plugin/11368-data-version-control-dvc-support)

## Gitlab Integrations

### Merge Request Integration CE - Code Review for GitLab

[Nhat's Team](https://plugins.jetbrains.com/organization/ntworld) 

 - 23+ Ratings  4.4 out of 5
 - 13,000+ Downloads
 - Apr 21, 2020

Merge Request Integration is a plugin which helps you to do Code Review right in your IDE.

What you can do:

1. Filter Merge Requests which are assigned to you, waiting for your approval, etc

2. Check pipeline status and approval status.

3. Do code review, navigate code with Diff View right in your IDE.

4. Add and reply a comment

5. Approve/revoke your approval

6. More and more features will be coming soon :)

Currently, the plugin supports GitLab only (gitlab cloud and self-hosted).

![image alt text](media/gitlab_merge_request_ce.png)

[https://plugins.jetbrains.com/plugin/13607-merge-request-integration-ce--code-review-for-gitlab](https://plugins.jetbrains.com/plugin/13607-merge-request-integration-ce--code-review-for-gitlab)

#### Other Gitlab plugins
[gitlab-quick-merge-request](https://plugins.jetbrains.com/plugin/11149-gitlab-quick-merge-request) - Just able to create a merge request

[gitlab-projects-2020](https://plugins.jetbrains.com/plugin/14110-gitlab-projects-2020) - Also offers gitlab integration (view merge requests, etc). Doesn't seem to support self-hosted.

## Jira Integration

[Adriel Saa Romano](https://gitlab.com/adrielsr/jira-intellij-plugin)  

- 23+ Ratings  3.2 out of 5
- 52,000+ Downloads
- Aug 02, 2020

Adds a small tab to show JIRA issues, etc.

![jira integrations](media/jira_integrations.png)

[https://plugins.jetbrains.com/plugin/11169-jira-integration](https://plugins.jetbrains.com/plugin/11169-jira-integration)

## Big Data Tools

[JetBrains s.r.o.](https://plugins.jetbrains.com/organization/JetBrains) 

- 11+ Ratings. 4.3 out of 5
- 184,000+ Downloads
- Jul 27, 2020

**Integrated tools for Zeppelin, Spark, and S3**

With this plugin, you can conveniently work with **Zeppelin** notebooks, **Spark** applications, and **S3** files right from **PyCharm**. 

Support should python zeppelin notebooks should be added soon.

![image alt text](media/big_data_tools.png)

[https://plugins.jetbrains.com/plugin/12494-big-data-tools](https://plugins.jetbrains.com/plugin/12494-big-data-tools)

## Jenkins Control Plugin

[Programisci.eu David Boissier, Yuri Novitsky (support of PPP), Michael Suhr](https://github.com/MCMicS/jenkins-control-plugin/issues)   

- 19+ Ratings. 3.7 out of 5   
- 188,000+ Downloads  
- Jul 28, 2020


**Integrates Jenkins in IntelliJ**

**Features:**

1. View Jobs

2. Trigger Jobs

3. Show Log for Job

4. Show Job Result as JUnit View

5. Multibranch support

[https://plugins.jetbrains.com/plugin/6110-jenkins-control-plugin](https://plugins.jetbrains.com/plugin/6110-jenkins-control-plugin)

# [Code tools](https://plugins.jetbrains.com/tag/15-code-tools)

## Save Actions

[Alexandre DuBreuil](https://www.github.com/dubreuia)

- 50+ Ratings. 4.7 out of 5
- 660,000+ Downloads  
- Feb 01, 2020

Helps configure "save actions" like, "optimize imports", "reformat code" and more on **every file save**.

![image alt text](media/save_actions.png)

**Very useful !**

[https://plugins.jetbrains.com/plugin/7642-save-actions](https://plugins.jetbrains.com/plugin/7642-save-actions)


## Python Annotations

[Meanmail](https://meanmail.ru/)  

- 15,000+ Downloads
- Apr 19, 2020

Implement some quick type hint code inspections and quickfixes.
```python
#### before

def str_to_int(value: str) -> Union[int, None]:

    ...

#### after quickfix

def str_to_int(value: str) -> Optional[int]:
```

![image alt text](media/python_annotation_suggestion.png)

Can be useful, at least not harmful.

[https://plugins.jetbrains.com/plugin/12035-python-annotations](https://plugins.jetbrains.com/plugin/12035-python-annotations)

## SonarLint

[SonarSource](https://www.sonarsource.com/)   

- 38+ Ratings.  3.3 out of 5
- 2,600,000+ Downloads
- Aug 18, 2020

Code inspection to find bug/vulnerabilities.
 
 ![image alt text](media/sonarlint.png)

[https://plugins.jetbrains.com/plugin/7973-sonarlint](https://plugins.jetbrains.com/plugin/7973-sonarlint)

## Pylint

[Roberto Leinardi](https://github.com/leinardi/pylint-pycharm) 119 350 Downloads

- 14+ Ratings.  4.2 out of 5
- 125,000+ Downloads
- Apr 25, 2020

This plugin provides both real-time and on-demand scanning of Python files with Pylint from within the PyCharm IDE.

![image alt text](media/pylint.png)

[https://plugins.jetbrains.com/plugin/11084-pylint](https://plugins.jetbrains.com/plugin/11084-pylint)

## Code Cleaner with Code Climate CL
[Nhat Phan](https://github.com/nhat-phan)  

- 2+ Ratings.  4.6 out of 5
- 3,000+ Downloads
- Dec 15, 2019

Implements code inspections to find different bad code smells (only works for linux/mac)

![image alt text](media/code_cleaner.gif)

[https://plugins.jetbrains.com/plugin/13306-code-cleaner-with-code-climate-cli](https://plugins.jetbrains.com/plugin/13306-code-cleaner-with-code-climate-cli)

# [Apps, Notification and Interaction Applications](https://plugins.jetbrains.com/tag/96-apps-notification-and-interaction-applications)

## Key Promoter X

[Hal's Corner](https://plugins.jetbrains.com/organization/halirutan)

- 345+ Ratings. 5.0 out of 5
- 1,317,000+ Downloads
- Jun 10, 2020

The Key Promoter X helps you to learn essential shortcuts while you are working.

![image alt text](media/key_promoter_x.gif)

**AWESOME. A MUST**

[https://plugins.jetbrains.com/plugin/9792-key-promoter-x](https://plugins.jetbrains.com/plugin/9792-key-promoter-x)

# [User Interface](https://plugins.jetbrains.com/tag/13-user-interface)

## CPU Usage Indicator

[Vojtech Krasa](https://github.com/krasa/CpuUsageIndicator) 

- 3+ Ratings. 4.7 out of 5
- 38,000+ Downloads
- Oct 23, 2017

![image alt text](media/cpu_usage.png)

[https://plugins.jetbrains.com/plugin/8580-cpu-usage-indicator](https://plugins.jetbrains.com/plugin/8580-cpu-usage-indicator)

## GPU Monitor

[Andrew Peng](https://andrewpeng.dev/)

- 1000+ Downloads
- Apr 06, 2020

**Works up to 2019.3.5**

Provides GPU stats from the IDE

![image alt text](media/gpu_monitor.png)

[https://plugins.jetbrains.com/plugin/13597-gpu-monitor](https://plugins.jetbrains.com/plugin/13597-gpu-monitor)

## Extra Icons

[Jonathan Lermitage](https://github.com/jonathanlermitage) 

- 12+ Ratings. 4.7 out of 5
- 182,000+ Downloads
- Aug 22, 2020

Add additional icons for files like Travis YML, Appveyor YML, etc.

![image alt text](media/extra_icons.png)

Would disable icons for common files like .gitignore and .md

[https://plugins.jetbrains.com/plugin/11058-extra-icons](https://plugins.jetbrains.com/plugin/11058-extra-icons)

## Rainbow Brackets

[Izhangzhihao](https://github.com/izhangzhihao)

- 90+ Ratings. 4.8 out of 5
- 3,000,000+ Downloads
- Jul 25, 2020

![image alt text](media/rainbow_brackets.png)

Pretty useful, very popular.

[https://plugins.jetbrains.com/plugin/10080-rainbow-brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)

# Themes

[Darcula Darker Theme - theme for IntelliJ IDEs](https://plugins.jetbrains.com/plugin/12692-darcula-darker-theme)

[Dark Purple Theme - theme for IntelliJ IDEs | JetBrains](https://plugins.jetbrains.com/plugin/12100-dark-purple-theme)

[One Dark theme - theme for IntelliJ IDEs](https://plugins.jetbrains.com/plugin/11938-one-dark-theme)

[Material Theme UI - theme for IntelliJ IDEs | JetBrains](https://plugins.jetbrains.com/plugin/8006-material-theme-ui)

# [Fun stuff](https://plugins.jetbrains.com/tag/16-fun-stuff)

## Power Mode II

[Alexander Thom](https://github.com/axaluss/power-mode-intellij-plugin)  

- 24+ Ratings. 4.7 out of 5
- 230,000+ Downloads

![image alt text](media/power_mode_ii.gif)

[Power Mode II - plugin for IntelliJ IDEs](https://plugins.jetbrains.com/plugin/8251-power-mode-ii)

## Progress Bars

[https://plugins.jetbrains.com/plugin/13709-dash-progress-bar](https://plugins.jetbrains.com/plugin/13709-dash-progress-bar)

[https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)

[https://plugins.jetbrains.com/plugin/14609-pokemon-trainer-progress-bar/](https://plugins.jetbrains.com/plugin/14609-pokemon-trainer-progress-bar/)

[https://plugins.jetbrains.com/plugin/14708-mario-progress-bar/](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar/)

[https://plugins.jetbrains.com/plugin/14725-sonic-progress-bar/](https://plugins.jetbrains.com/plugin/14725-sonic-progress-bar/)

[https://plugins.jetbrains.com/plugin/14726-zelda-progress-bar/](https://plugins.jetbrains.com/plugin/14726-zelda-progress-bar/)

One is a must.

# [Version Control](https://plugins.jetbrains.com/tag/6-version-control)

## .ignore

[Hsz](http://ignore.hsz.mobi/)  

- 73+ Ratings. 4.0 out of 5
- 10,431,000+ Downloads
- Jul 31, 2020

**.ignore** is a plugin for *.gitignore (Git), .hgignore (Mercurial), .npmignore (NPM), .dockerignore (Docker)*

![image alt text](media/ignore.png)

[https://plugins.jetbrains.com/plugin/7495--ignore](https://plugins.jetbrains.com/plugin/7495--ignore)


## Conventional Commit

[Edoardo Luppi](https://github.com/lppedd/idea-conventional-commit)  

- 3+ Ratings. 4.7 out of 5
- 7,707+ Downloads  
- Jun 10, 2020

The aim of this plugin is to provide completion for [conventional commits](https://conventionalcommits.org/), also named *semantic commits*, inside the VCS Commit dialog.

![image alt text](media/conventional_commit.gif)

Very flexible and fluent. However, it doesn't **enforce**.

[https://plugins.jetbrains.com/plugin/13389-conventional-commit](https://plugins.jetbrains.com/plugin/13389-conventional-commit)

**Extension for commitlint**

[https://github.com/lppedd/idea-conventional-commit-commitlint](https://github.com/lppedd/idea-conventional-commit-commitlint)

# [Editor](https://plugins.jetbrains.com/tag/25-editor)

## Quick File Preview

[Martin Sommer](https://github.com/SeeSharpSoft/intellij-file-preview)  

- 29+ Ratings. 5.0 out of 5
- 60,000+ Downloads
- Apr 26, 2020

Opens window on file click. Closes window after clicking on a different file.

![image alt text](media/quick_file_preview.png)

[https://plugins.jetbrains.com/plugin/12778-quick-file-preview/](https://plugins.jetbrains.com/plugin/12778-quick-file-preview/)


## Python custom import
orleviad

- 3000+ Downloads
- Apr 27, 2020

Plugin that copy import in python interpreter style.
Very useful for various scenarios such as copying imports to notebook.

![image alt text](media/copy_as_import1.bmp)
Paste anywhere:
![image alt text](media/copy_as_import2.bmp)

[https://plugins.jetbrains.com/plugin/12857-python-custom-import](https://plugins.jetbrains.com/plugin/12857-python-custom-import)

# [Languages](https://plugins.jetbrains.com/tag/48-languages)

## CSV Plugin

[Martin Sommer](https://github.com/SeeSharpSoft/intellij-csv-validator) 

- 20+ Ratings. 4.3 out of 5
- 4,370,000+ Downloads
- Aug 13, 2020

Lightweight plugin for editing CSV/TSV/PSV files with a flexible table editor, syntax validation, structure highlighting, customizable coloring, new intentions and helpful inspections.

![image alt text](media/csv_plugin.png)

[https://plugins.jetbrains.com/plugin/10037-csv-plugin](https://plugins.jetbrains.com/plugin/10037-csv-plugin)

## BashSupport

[Joachim Ansorg](https://www.plugin-dev.com/)

- 110+ Ratings. 4.6 out of 5
- 14,000,000+ Downloads
- Jul 24, 2020

Bash language support for the IntelliJ platform.

Supports run configurations, syntax highlighting, rename, documentation lookup, inspections, quickfixes and more.

Retired for newer jetbrains products (BashSupport pro exists). As "Shell Script" was bundled with the jetbrains platform.

[https://plugins.jetbrains.com/plugin/4230-bashsupport](https://plugins.jetbrains.com/plugin/4230-bashsupport)

# [Spellcheck](https://plugins.jetbrains.com/tag/179-spellcheck)

## Grazie

[JetBrains s.r.o.](https://plugins.jetbrains.com/organization/JetBrains) 

- 29+ Ratings. 4.9 out of 5
- 186,000+ Downloads
- Jul 16, 2020

Provides intelligent spelling and grammar checks for text that you write in the IDE.

Supports over 15 languages, including English, German, Russian, Chinese, and others.

![image alt text](media/grazie.gif)

[https://plugins.jetbrains.com/plugin/12175-grazie](https://plugins.jetbrains.com/plugin/12175-grazie)

# [PDF](https://plugins.jetbrains.com/tag/55-pdf)

## PDF Viewer

[FirstTimeInForever](https://github.com/FirstTimeInForever/intellij-pdf-viewer)

- 4+ Ratings. 4.7 out of 5
- 350+ Downloads
- Jul 10, 2020

PDF viewer inside the IDE.  

[https://plugins.jetbrains.com/plugin/14494-pdf-viewer](https://plugins.jetbrains.com/plugin/14494-pdf-viewer)

# [Reporting](https://plugins.jetbrains.com/tag/39-reporting)

## WakaTime

[WakaTime](https://wakatime.com/)  

- 9+ Ratings. 4.5 out of 5
- 415,000+ Downloads
- Mar 06, 2020

Tracks IDE times, sends to a web service which then shows visualizations of it.

![image alt text](media/wakatime.png)

[WakaTime - plugin for IntelliJ IDEs | JetBrains](https://plugins.jetbrains.com/plugin/7425-wakatime)


[Code Time - plugin for IntelliJ IDEs | JetBrains](https://plugins.jetbrains.com/plugin/10687-code-time/) is a similar alternative

# [Viewer](https://plugins.jetbrains.com/tag/56-viewer)

## OpenCV Image Viewer

Adrian Boguszewski  

- 1+ Rating. 4.5 out of 5
- 600+ Downloads
- Jul 31, 2020

Treats numpy array as an image and displays its content.

![image alt text](media/opencv_image_viewer.gif)

If you use images in numpy arrays, why not ?

[https://plugins.jetbrains.com/plugin/14371-opencv-image-viewer](https://plugins.jetbrains.com/plugin/14371-opencv-image-viewer)

# [Miscellaneous](https://plugins.jetbrains.com/tag/104-miscellaneous)

## Archive browser
[Ilya Usanov](https://github.com/b3er/idea-archive-browser)

- 18+ Ratings. 4.1 out of 5
- 75,000+ Downloads
- Mar 30, 2019

[archive-browser](https://plugins.jetbrains.com/plugin/9491-archive-browser)

This plugin allows you to browse most archives like folders in IDEA.

## Dictionary

[Lost-World](https://github.com/olivernybroe/intellij-Dictionary)  

- 2+ Ratings. 4.6 out of 5
- 1,120 Downloads
- Mar 20, 2019

Plugin for having a shared dictionary for all members of your project.

**Great idea!** Takes some restarting and moving the ‘project.dic’ file to work.

[Dictionary - plugin for IntelliJ IDEs](https://plugins.jetbrains.com/plugin/12089-dictionary)

## PyCharm Help

[JetBrains s.r.o.](https://plugins.jetbrains.com/organization/JetBrains)   

- 16,000+ Downloads

PyCharm Web Help for offline use.

[https://plugins.jetbrains.com/plugin/9993-pycharm-help](https://plugins.jetbrains.com/plugin/9993-pycharm-help)

# [Code editing](https://plugins.jetbrains.com/tag/89-code-editing)

## Emoji Support Plugin

[Shiraji](http://github.com/shiraji)

[Emoji Support Plugin - IntelliJ IDEs](https://plugins.jetbrains.com/plugin/9174-emoji-support-plugin)

[Yet another emoji support - IntelliJ IDEs](https://plugins.jetbrains.com/plugin/12512-yet-another-emoji-support)

- 8+ Ratings. 4.0 out of 5
- 25,000+ Downloads
- Apr 11, 2020


Emoji support inside the IDE

![image alt text](media/emoji_support.gif)

Both from the same author, YAES seems to be newer but both are maintained.

Might be useful for teams when coordinating emoji meanings.
However, colorful emojis are only in mac OS :( [link](https://stackoverflow.com/questions/43004882/how-to-add-an-emoji-to-comment-in-intellij-idea-2017-1/43005177)

This is how it looks on Linux/Windows.

![image alt text](media/emoji_linux.png)


# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/jonzarecki/awesome-pycharm-plugins/blob/master/CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could [vote for them](https://github.com/jonzarecki/awesome-pycharm-plugins/pulls) by adding :+1: to them. Pull requests will be merged when their votes reach **5**.

- - -

If you have any question about this opinionated list, do not hesitate to open an issue on GitHub.
