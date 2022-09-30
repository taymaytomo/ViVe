# ViVe
ViVe is a C# library you can use to make your own programs that interact with the A/B feature experiment mechanism found in Windows 10 & newer.

The *FeatureManager* class should cover most feature management needs with the added benefit of some struct heavy lifting being done for you. Boot persistence and LKG management is offered exclusively by this class as it had to be reimplemented.

In case you'd like to talk to NTDLL exports directly, you can use *NativeMethods*.

# ViVeTool
ViVeTool is both an example of how to use ViVe, as well as a straightforward tool for power users which want to use the new APIs instantly.

[![Release downloads](https://img.shields.io/github/downloads/thebookisclosed/ViVe/total.svg)](https://GitHub.com/taymaytomo/ViVe/releases/)

# Compatibility
In order to use ViVe, you must be running Windows 10 build 18963 or newer.

![ViVeTool Helpfile](https://github.com/taymaytomo/ViVe-master/blob/main/Compatibility.png)

# How to Enable TAB File Explorer Windows 11 22H2
- First please download Vivetool https://github.com/taymaytomo/ViVe/releases

- After that extract the file by right-clicking select extract all then navigate to Drive C:\Windows\System32

- Next press the start menu, type CMD then right-click on windows terminal and select Run as Administrator

- Then type the following commands in turn and enter:

- ### vivetool /enable /id:37634385
- ### vivetool /enable /id:39145991

- After that restart your computer and congratulations the Tab File Explorer feature of Windows 11 22H2 is active

