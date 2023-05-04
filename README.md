# Jicop-H00k
This repository is meant to host the core files needed to create a Beacon Object File for use with AM0N-Eye. A Beacon Object File (BOF) is a compiled C program, written to a convention that allows it to execute within a Beacon process and use internal Beacon APIs. 
BOFs are a way to rapidly extend the Beacon agent with new post-exploitation features.
Inject shellcode (either custom or beacon) into remote process using NtOpenProcess - NtAllocateVirtualMemory - NtWriteVirtualMemory .

Build: i686-w64-mingw32-gcc JicopH00k.c -o JicopH00k.exe -lws2_32
Use : ./command_control ip_address port

Here I was trying on the Kaspersky AV & Hunters Against EDR


https://user-images.githubusercontent.com/121706460/236143988-70bb1c5f-dc2d-43e6-9ed9-d39b5bf8f307.mp4

