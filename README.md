# Automatic control system of a water-heating boiler

This is a demonstration project for an automatic control system of a water-heating boiler. Repo contains project backups and PLC sources written in SCL.

## Requirements

- Windows 10 or Windows 11.
- Step 7 V5.7 or above.
- S7-PLCSIM V5.4 SP8 or above.
- WinCC V8.0 or above.

## Deployment

***Security features are disabled intentionally to make launching the project easier.***

1. Retrieving the PLC project.
1. Run PLCSIM.
1. Compile and download project to PLCSIM.
1. Set controller to Run in PLCSIM.
1. Unzip the SCADA project.
1. Open the WinCC Explorer.
1. Press open and navigate to the unzipped project folder.
1. In computer settings change Name to your computer name.
1. Press Run button to start the project.
1. In system menu click LogOn button and enter username Administrator and password Administrator to access all restricted tabs and features.

## User manual

By default system in simulation mode. Boiler, pumps and fans on scada are clickable and has pop-up menus. To access config user has to be Administrator(same password). To start boiler open corresponding pop-up menu and press start. After stop boiler has to be reset(press Reset button). To start circulating pump and level control press ON buttons on corresponding controllers. To change simulation parameters press simulation button on the main screen.
