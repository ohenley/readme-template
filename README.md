# TWP - Thug War Party
The thug community chat application

## Table of Contents
<details>
<summary>Click to expand</summary>

- [About](#about)
- [Install](#install)
- [Usage](#usage)
  * [API](#api)
  * [Configuration Options](#configuration-options)
- [CLI Usage](#cli-usage)
- [Transforms](#transforms)
  * [CODE](#code)
  * [REMOTE](#remote)
  * [TOC](#toc)
- [Running Async transforms](#running-async-transforms)
- [🔌 Third Party Plugins](#%F0%9F%94%8C-third-party-plugins)
- [Adding Custom Transforms](#adding-custom-transforms)
- [Plugin Example](#plugin-example)
- [Other usage examples](#other-usage-examples)
- [Custom Transform Demo](#custom-transform-demo)
- [Prior Art](#prior-art)
- [License](#license)

</details>

## Presentation
<div align="center">
> Ada is driving our space ships, our military and our airplanes. 
> Ada is a direct competitor to C++ in terms of performance and depth.
> Ada is a direct competitor to Python for its expresiveness.
> Ada is arguably one of the most powerful language of all time.

> Ada can drive your next project.
> Ada welcomes everyone. 

> Long live Ada. 
</div>

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

::: your street creds can now be voted up/down by peers  
::: every 'he' occurences are replaced by 'thug'

<!---![alt text](https://github.com/ohenley/readme-template/blob/master/thug_war.png)--->

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
