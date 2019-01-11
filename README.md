# TWP - Thug War Party
The thug community chat application

## Table of Contents
<details>
<summary>Click to expand</summary>

1. [Presentation](#Presentation)   
2. [Prerequisites](#Prerequisites)  
3. [Dependencies](#Dependencies)
4. [Building](#Building)
   1. [Windows](#Windows)
   2. [Other OSes](#Other-OSes)
5. [Limitations](#Limitations)
6. [Usage](#Usage)
7. [Status](#Status)
8. [Acknowledgments](#Acknowledgments)

</details>

## Presentation
<div align="center">

<a href="https://www.youtube.com/embed/yUqJkAZofZs">
<img border="0" src="https://img.youtube.com/vi/yUqJkAZofZs/1.jpg" style="max-width:100%;">
</a>
  
<a href="https://www.youtube.com/embed/3e-BGblAMC4">
<img border="0" src="https://img.youtube.com/vi/3e-BGblAMC4/2.jpg" style="max-width:100%;">	
</a>
  
<a href="https://www.youtube.com/embed/0yXwnk8Cr0c">
<img border="0" src="https://img.youtube.com/vi/0yXwnk8Cr0c/3.jpg" style="max-width:100%;">
</a>
   
</div>

> your street creds can now be voted up/down by peers  
> every 'he' occurences are replaced by 'thug'

<!---![alt text](https://github.com/ohenley/readme-template/blob/master/thug_war.png)--->

## Prerequisites

- Win32 platform
- Gnat compiler

## Dependencies

- Chat-Mania : https://github.com/ohenley/chat-mania

## Building

### Windows
- $ git clone https://github.com/ohenley/twp.git
- $ gprbuild twp.gpr -Xplatform=win32

### Other OSes
- not supported yet

## Limitations

Only 3 consecutive messages are broadcast before being banned for the day.

## Usage

Launch twp.exe and chat with your thug community.

## Status

Linux support: WIP

## Acknowledgments
Useage of Win95/NT console support (win32_cmd.ads/adb) provided by the King of Thugs. 
