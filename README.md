# DSP

<p align="center">
    <img src="DSP.gif" />
</p>


## About the Projects

These Projects are part of the SBE 309 Medical Signal Processing Curriculum at the Faculty of Engineering, Cairo University

## Prerequisites

A good Understanding of **Python** Programming Language and one of its GUI Components (PyQt5)\
Some Familarity with some of python third party packages like **numpy**, **matplotlib** would be a plus\
basic understanding of the main concepts of OOP is a plus

However, you can apply the concepts of the projects with any other prefered programming language

## Projects List

|  # |                                       Project Name                                       |          Status          |
|:--:|:----------------------------------------------------------------------------------------:|:------------------------:|
| 01 | [multiChannelSignalViewer](https://github.com/RamadanIbrahem98/multiChannelSignalViewer) |    :heavy_check_mark:    |
| 02 |          [sound-equalizer](https://github.com/RamadanIbrahem98/sound-equalizer)          |    :heavy_check_mark:    |
| 03 |          [kiss-ft-and-fft](https://github.com/RamadanIbrahem98/kiss-ft-and-fft)          |    :heavy_check_mark:    |
| 04 |              [image-mixer](https://github.com/RamadanIbrahem98/image-mixer)              |    :heavy_check_mark:    |
| 05 |             [Shazam-Clone](https://github.com/RamadanIbrahem98/Shazam-Clone)             | :hourglass_flowing_sand: |

<br/>

## 01 - [multiChannelSignalViewer](https://github.com/RamadanIbrahem98/multiChannelSignalViewer)

This Project is the first project in the semester and does not use any digital signal processing concepts yet. It is just a warm up to get comfortable using the GUI components

### Project Description

you are required to design a multi-channel (i.e. three) signal viewer
<br/>
this application should present the signal in real-time like with the ability to play, pause, zoom in and out, auto pan the signal, move forward or backward in time, and change the speed of the signal
<br/>
it is also required to have the ability to export the current scene as a PDF report
<br/>
This PDF should be dynamic, meaning if I'm handling only one channel, it would generate the report for that one channel only. And if I'm using more than one channel, it should extract all of them and try fit them in the PDF as considered best fit
<br/><br/>
Final requirement is presenting the Spectrogram of the time signal, at this point of time, you are not required to have a broad understading of the subject, just the basics of spectrogram and what it represents

type of signal to use: any open-source medical signal (i.e. ECG, EEG, EMG, ...etc)

### progress in first project

|  # | [multiChannelSignalViewer](https://github.com/RamadanIbrahem98/multiChannelSignalViewer) |          Status          |
|:--:|:----------------------------------------------------------------------------------------:|:------------------------:|
| 01 |                   Download And Filter Some Open-Sourse Medical Signals                   |    :heavy_check_mark:    |
| 02 |                                      Create the GUI                                      |    :heavy_check_mark:    |
| 03 |                              Display the Signal in Real-time                             |    :heavy_check_mark:    |
| 04 |                                 Add Play, Pause Controls                                 |    :heavy_check_mark:    |
| 05 |                               Add Zoom in and out Controls                               |    :heavy_check_mark:    |
| 06 |                                       Add Print PDF                                      |    :heavy_check_mark:    |
| 07 |                                      Add Spectrogram                                     |    :heavy_check_mark:    |
| 08 |                                        Add Autopan                                       |    :heavy_check_mark:    |
| 09 |                            Add Move Forward, Backward in time                            | :hourglass_flowing_sand: |
| 10 |                           Add Speed Control, Speed up and down                           | :hourglass_flowing_sand: |
| 11 |                    Refactor the Spectrogram and use the Matplotlib one                   | :hourglass_flowing_sand: |


## 02 - [sound-equalizer](https://github.com/RamadanIbrahem98/sound-equalizer)

This is the second project in the semester and the first project using Fast Fourier Transform (fft) to process audio files (mainly wav)

### Project Description

You are required to design a GUI application to load and play audio files. when loaded, you should plot the waveform and move it real-time in sync with the audio and plot the signal's spectrogram.
<br>
You have to control this audio signal (play, pause, stop) and manipulate the waveform and spectrogram (zoom in and out, move forward, backward) all of this happen in sync (any movement in audio appear in waveform and spectrogram and vice versa)
<br>
Humans can only hear from 20HZ to 20KHZ and that depends on age and other medical factors
<br>
You are required to slice the range of frequency into 10 bands, then create 10 sliders to control the magnitude of the signal at those bands. It should goes from [0 to 5] times the magnitude
<br>
after any change in the equalizer, an after waveform and spectrogram are generated next to the original ones to show the difference between them
<br><br>
as for the spectrogram, you should have the ability to:

* choose a color palette from a list of different color palettes
* control the minimum and maximum magnitude (in db), that controls the color intensity, any value that is less than the minimum or greater than the maximum should be saturated
<br><br>

just like project 1 you should have a generate PDF button to extract the current view of the waveform and spectrogram before and after equalization
<br><br>

The Application should have a signal for creating a new instance (New Window)
### progress in the second project

|  # | [sound-equalizer](https://github.com/RamadanIbrahem98/sound-equalizer) |       Status       |
|:--:|:----------------------------------------------------------------------:|:------------------:|
| 01 |                       Download wav samples online                      | :heavy_check_mark: |
| 02 |                             Create the GUI                             | :heavy_check_mark: |
| 03 |              Create controls to play, pause and stop audio             | :heavy_check_mark: |
| 04 |       Sync audio playback with waveform and spectrogram position       | :heavy_check_mark: |
| 05 |                           Get the signal fft                           | :heavy_check_mark: |
| 06 |          Manipulate Each pin with the slider equivalent value          | :heavy_check_mark: |
| 07 |                          Add palettes combobox                         | :heavy_check_mark: |
| 08 |                              Add Print PDF                             | :heavy_check_mark: |
| 09 |                   Add Spectrogram Min and Max decible                  | :heavy_check_mark: |
| 10 |                      Add new window functionality                      | :heavy_check_mark: |

## Our Team

-   Ramadan Ibrahem - [![linkedin-shield]](https://www.linkedin.com/in/ramadanibrahem/)
-   Muhammad Seyam - [![linkedin-shield]](https://www.linkedin.com/in/mohamed-seyam-91b3b81b7/)
-   Muhammad Abd-ElAziz - [![linkedin-shield]](https://www.linkedin.com/in/mohamed-ahmed-abdelaziz)
-   Yousef Samir - [![linkedin-shield]](https://www.linkedin.com/in/youssef-samir-b24848191)

## Supervision

DR. Tamer Basha
<br/>
T.A. Christina Adly

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555