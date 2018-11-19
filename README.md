4d-plugin-process-information
=============================

4D implementation of the ProcessInfo class. Maybe useful to control App Nap in 10.9. Also commands to read command line arguments (Mac and Win).

**Note**: The cross-platfrom portion of this plugin is available as [plugin-process](https://github.com/miyako/4d-plugin-process).

### Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />||<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|


Commands
---

```c
// --- Process Information (10.0)
PROCESS_GET_ARGUMENTS
PROCESS_Get_name
PROCESS_Get_identifier
PROCESS_SET_NAME
PROCESS_Get_GUID
PROCESS_LOG

// --- App Nap (10.9)
END_IMPORTANT_ACTIVITY
BEGIN_IMPORTANT_ACTIVITY

// --- System Information (10.5)
SYSTEM_Get_cores
SYSTEM_Get_cores_active

// --- System Information (10.6)
SYSTEM_Get_uptime

// --- System Information (10.0)
SYSTEM_Get_version
SYSTEM_Get_computer_name
SYSTEM_Get_name
```
