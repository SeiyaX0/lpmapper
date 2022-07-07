# lpmapper

A mapper that maps shellcode into loaded large page drivers without allocating any memory.

This concept requires you to set the HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management\LargePageDrivers value in the registry. This project can be used to get around common detection methods imposed by kernel-mode anti-cheats, such as BattlEye or EasyAntiCheat.
