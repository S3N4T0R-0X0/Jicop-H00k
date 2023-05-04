# Jicop-H00k
This repository contains the core files required to create a Beacon Object File (BOF) for use with AM0N-Eye. BOFs are compiled C programs written in a specific convention that allows them to execute within a Beacon process and use internal Beacon APIs. BOFs provide a fast and efficient way to extend the Beacon agent with new post-exploitation features.

The included BOF, "JicopH00k.c," allows you to inject shellcode (custom or Beacon-generated) into a remote process using the following sequence: NtOpenProcess -> NtAllocateVirtualMemory -> NtWriteVirtualMemory.

To build the BOF, use the following command: i686-w64-mingw32-gcc JicopH00k.c -o JicopH00k.exe -lws2_32

Once compiled, the BOF can be executed with the following command: ./command_control ip_address port

Please note that the purpose of this repository is to provide a technical demonstration only and should not be used for any malicious or illegal activities.

Here I was trying on the Kaspersky AV & Hunters Against EDR


https://user-images.githubusercontent.com/121706460/236143988-70bb1c5f-dc2d-43e6-9ed9-d39b5bf8f307.mp4

