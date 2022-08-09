# Magisk and GApps on WSA

## Star (if you like) and fork this repo
   ![Fork](https://docs.github.com/assets/images/help/repository/fork_button.jpg)
## Go to the **Action** tab in your forked repo
   ![Action Tab](https://docs.github.com/assets/images/help/repository/actions-tab.png)
## In the left sidebar, click the **Automate** workflow.
   ![Workflow](https://docs.github.com/assets/images/actions-select-workflow.png)
## Above the list of workflow runs, select **Run workflow**
   ![Run Workflow](https://docs.github.com/assets/images/actions-workflow-dispatch.png)
## Input the download link of Magisk and select the [OpenGApps variant](https://github.com/opengapps/opengapps/wiki#variants) (none is no OpenGApps) you like and click **Run workflow**
   ![Run Workflow](https://docs.github.com/assets/images/actions-manually-run-workflow.png)
## Wait for the action to complete and download the artifact
   ![Download](https://docs.github.com/assets/images/help/repository/artifact-drop-down-updated.png)
## Unzip the artifact and uninstall WSA if you have an official installation or replace the previously unzipped artifact if you have a manual installation
1. Enable developer mode on Windows
1. Right-click `Install.ps1` and select `Run with PowerShell`
1. Launch WSA and enable developer mode, launch the file manager, and wait until the file manager popup
