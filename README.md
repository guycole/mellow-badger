# mellow-badger 
Mellow Badger enables control of a [RTL-SDR](https://www.rtl-sdr.com) USB dongle using a REST framework.

## Introduction
Mellow Badger provides a REST application which can control a [RTL-SDR](https://www.rtl-sdr.com) USB dongle.  The overall goal is to control a family of single board computers (such as the [Raspberry Pi](https://www.raspberrypi.org/) to perform automated signal collection.  A fleet of inexpensive computers and receivers can have impressive capabilities, especially for narrowband collection tasks.

Mellow Badger emphasizes autonomous operation over manual, so there is no user interface.  Audio is produced, but the emphasis is on recording or writing to a remote network host. 

## Features
1. Chanel watch, i.e. dial to specific frequency and stream.
1. Scan discrete frequencies, sample when active (various sample modes, i.e. record a few seconds, record until silent, etc)
1. Search for activity between an upper and lower frequency, write observations to log, record for a few seconds, etc)
1. Save observation files to local file system.
1. Stream audio to local audio, or via network (RTP/RTSP)
1. Support prometheus scrape
