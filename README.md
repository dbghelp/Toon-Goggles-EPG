# Toon-Goggles-EPG
XML EPG for Toon Goggles channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for Toon Goggles channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/Toon-Goggles-EPG/refs/heads/main/tg.xml

## Features

- XML formatted EPG for Toon Goggles channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Toon-Goggles-EPG/refs/heads/main/tg.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Toon-Goggles-EPG/refs/heads/main/tg.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id                       | Channel Name                           |
|------------------------------|----------------------------------------|
| 261204                       | Toon Goggles                           |
| 282381                       | AfroKiddos                             |
| 286328                       | Mega Machines Channel (MMC)            |
| 273082                       | Smurf TV                               |
| 261896                       | Sparkle Power                          |
| 266201                       | Toon Goggles en Español                |
| 273084                       | Pitufo TV                              |
| 264166                       | Camp Spoopy                            |
| 267344                       | Guinness World Records                 |
| 264556                       | Eddie's Wonderland                     |
| 261882                       | Gross Out TV                           |
| 264523                       | TG Movies                              |
| 259931                       | ZooMoo                                 |
