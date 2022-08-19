### THIS ORGANIZATION IS AN ARCHIVE
Links are broken, repos don't exist, the whole shebang. You probably wanted to visit the main [CWRUBotix organization](https://github.com/cwruRobotics).
The remainder of this file is the old readme.
***

# CWRUBotix MATE ROV
[Competition link](https://materovcompetition.org/explorerspecs)

For software team: If you're a new 'round here, take a look at one of the setup sections.

## Bootcamp Setup
If the year's just starting and you're joining MATE ROV for our team-specific bootcamp, check out the [rov-bootcamp setup](https://github.com/CWRUbotixROV/rov-bootcamp). Once we've finished bootcamp, come back here and read the next section.

## Season Setup
Follow the [rov-vision-22 setup guide](https://github.com/CWRUbotixROV/rov-vision-22/wiki/Repo-Setup). This guide covers setting up our main code in its own Python virtual environment (for isolating dependencies on a per-project basis).

Follow the [ardupilot_gazebo setup guide](https://github.com/CWRUbotixROV/ardupilot_gazebo/wiki/Setup). This guide covers setting up Ardupilot (specifically Ardusub, which controls & listens to our bot), Gazebo (for virtual testing), OpenCV (for graphics manipulation in Python) and GStreamer (for streaming video from our cameras and pain).

You should end up with clones of the [rov-vision-22](https://github.com/CWRUbotixROV/rov-vision-22) and [data]() repos from the rov-vision-22 setup, and clones of the [opencv](https://github.com/opencv/opencv), [ardupilot](https://github.com/CWRUbotixROV/ardupilot), [ardupilot_gazebo](https://github.com/CWRUbotixROV/ardupilot_gazebo), and [gazebo_rov](https://github.com/CWRUbotixROV/gazebo_rov) repos from the ardupilot_gazebo setup.

## Repos
### Active repos
#### Main
- [rov-vision-22](https://github.com/CWRUbotixROV/rov-vision-22) - the current control station code (e.g. vision, tasks, & GUI)
- [ardupilot](https://github.com/CWRUbotixROV/ardupilot) - our fork of Ardupilot/Ardusub
- [ardupilot_gazebo](https://github.com/CWRUbotixROV/ardupilot_gazebo) - our fork of a Gazebo plugin that integrates Ardupilot into Gazebo simulations
  
  Note: modify `src/freebuoyncy.cpp` to change random currents
- [gazebo_rov](https://github.com/CWRUbotixROV/gazebo_rov) - our Gazebo simulation worlds & models
- [companion](https://github.com/CWRUbotixROV/companion) - code that runs on the Raspberry Pi (e.g. video streaming, talking to MAVLink)

#### Misc
- [rov-bootcamp](https://github.com/CWRUbotixROV/rov-bootcamp) - code from the MATE ROV software team bootcamp
- [.github-private](https://github.com/CWRUbotixROV/.github-private) - the repo containing this file, contains MATE ROV-wide docs visible to members of CWRUBotixROV only

### Old repos
- [rov-vision](https://github.com/CWRUbotixROV/rov-vision) - 18-19 & 20-21 control station code
- [Firmware](https://github.com/CWRUbotixROV/Firmware) - 18-19 & 19-20 firmware code & docs

### Are we using these forks?
- [MAVProxy](https://github.com/CWRUbotixROV/MAVProxy) - fork of ArduPilot/MAVProxy
- [mavlink](https://github.com/CWRUbotixROV/mavlink) - fork of ArduPilot/mavlink
- [qgroundcontrol](https://github.com/CWRUbotixROV/qgroundcontrol) - fork of mavlink/qgroundcontrol
