# TWP - Thug War Party
The thug community chat application

<---![alt text](https://github.com/ohenley/readme-template/blob/master/thug_war.png)--->

::: your street creds can now be voted up/down by peers  
::: every 'he' occurences are replaced by 'thug'

## Prerequisites

- Win32 platform
- Gnat compiler

## Dependencies

- Chat-Mania : https://github.com/ohenley/chat-mania

## Building

- $ git clone https://github.com/ohenley/twp.git
- $ gprbuild twp.gpr -Xplatform=win32

## Limitations

Only 3 consecutive messages are broadcast before being banned for the day.

## Usage

Launch twp.exe and chat with your thug community.

## Status

Linux support: WIP

## Acknowledgments
Useage of Win95/NT console support (win32_cmd.ads/adb) provided by the King of Thugs. 
