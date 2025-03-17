# Alfred-workflow-move-to-new-folder
# Introduction

This workflow takes a file or files selected in Finder and moves them to a folder which is newly created in the course of the workflow. You are prompted for the location of the new folder and for the name of the new folder.

# Usage

1. Simply select a file or files in Finder, press your Universal Action hotkey (`⌘ + /` by default) and, if this workflow title does not appear at the top of the list of your Universal Actions, start typing `Move` until you see the name of this workflow.

![UA](https://github.com/user-attachments/assets/e0265553-4d41-420f-9d7c-3a8e58f97362)

2. Choose the folder in which you wish to create the new folder. Just start typing the name of the folder to see a list of matching folders from which you can select the appropriate one. (See also the important note below about discovery of folders.)

![BaseFolder](https://github.com/user-attachments/assets/dd627143-11a1-49af-bc5f-3a23241e7147)

3. You will then be prompted for the name of the new folder.

![NewFolder](https://github.com/user-attachments/assets/98434b35-ff95-4a8e-a273-3bad3dae5e6f)

The new folder will be created and the files moved (not copied) to it—with a notification to confirm what has happened.

# Important notes

- In order for a folder to be found in the second step of the workflow *it must be within your default search scope*. (See `Alfred Preferences → Features → Default Results` and look under `Search Scope`.) However, if you want to be able to find folders outside that scope just double click on the workflow `File Filter`, go to `Scope` and drag in the folder(s) you wish to be included within the file filter search scope. *Note that if you do that you'll also as well have to drag in the folders that are within your Alfred search scope*. If you don't do that the folder search will be limited only to the new folders you have dragged in.
- The sound can be muted within this configuration (see the checkbox opposite).
- If there already exists in the destination folder a folder with the same name as that you have proposed you will be warned and must end the workflow. In other words, this workflow will not overwrite an existing folder.

# Acknowledgement

I am indebted to @sepulchra on the [Alfred forum](https://www.alfredforum.com/) for the provocation to write this workflow but, particularly, for invaluable help and advice developing and testing the workflow. However, if there are errors or infelicities in the final workflow they are mine.
