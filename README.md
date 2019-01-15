# Myriota Dev Kit Setup

The IoT Auckland Meetup had a two day hackathon workshop to trial out the Myriota dev kit and below are some thoughts and experiences from the setup.

What we set out to achieve was the dev kit setup and use of the examples as tutorials.  We gained good experience of the practical steps of following the tutotial that Myriota provide and what is required to use the kit.

<h2>1/  Software Dev Environment</h2>
Using a Windows 10 PC, the setup of Windows Systesm for Linux and Ubuntu was very straightforward to complete and worked exactly as expected.  I recommend using this.

The tip I suggest is to setup a symbolic directory link from the Windows file system to the Ubuntu home directory.  This is more convenient for accessing the Myriota SDK.
i.e.  download and unzip the Myriota SDK to a convenient Windows directory.  Under Ubuntu create a symbolic link to the Windows directory.

![](Screenshot%20(47).png)


<h2>2/  Use a Raspberry Pi for the Satellite Simulator</h2>
Here you see the satellite simulator setup on a Raspberry Pi with the SDR dongle connected.  The Myriota dev board is adjacent.
![](IMG_20190115_152005176.jpg)

The advantage of this is that the satellite simulator is now running independently from the dev board software environment.

The Rasperry Pi is setup with the standard Raspian OS, and SSH access is enabled.  The Myriota SDK is copied on the R-Pi, I installed the SDK to ensure the SDR was setup correctly, though the gcc compiler is unnecessary.

It's also practical to open further SSH sessions to the R-Pi to monitor message upload.


