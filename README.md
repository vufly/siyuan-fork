This is a forked version of [Siyuan Android app](https://github.com/siyuan-note/siyuan-android)  with a modified workspace management approach.

## Why this fork?

The original Siyuan Android app stores workspaces in an app-specific directory, which prevents third-party apps from accessing the data. This limits the ability to use third-party synchronization services. This fork addresses this issue by:

- Allowing users to choose a folder in shared storage as the home directory for their workspaces.
- Saving and loading workspaces from the chosen folder, enabling access by third-party apps for synchronization.

## Warning

- It's highly recommended that you regularly back up your data. I cannot be held responsible for any loss or corruption of your workspaces.
- By storing your workspaces in shared storage, you acknowledge that the data is now accessible to other apps on your device that have the necessary permissions. This could pose a security risk if such apps are malicious.

## Downloads

You can get the APK from [releases page](https://github.com/vufly/siyuan-fork/releases) or build it yourself with [the original guide](https://github.com/siyuan-note/siyuan-android?tab=readme-ov-file#construction-guide).

## Acknowledgement

This fork incorporates some code from the Logseq project, specifically the [FileUtil.java](https://github.com/logseq/logseq/blob/master/android/app/src/main/java/com/logseq/app/FileUtil.java) class.
