# EcoWitt to ASCOM platform connector

This driver is my first experiment in C# and with the ASCOM platofrm.

Anyway, this driver is able to read the data provided by your EcoWitt weather station and pass the data to ASCOM platform.

Actually I test it only with the WS90 weather station reading the data from the GW2001 hub.

## Setup

Start the installation, and click next everytime

## Before start

Open your preferite software, I use N.I.N.A., when you need to choose the driver open the setup page:

![image](https://github.com/user-attachments/assets/80f09ad6-dea8-41cb-9188-c109f6a8de05)

Out the IP address of your weather station, and click Test!

If everything is good this message will appear:

![image](https://github.com/user-attachments/assets/2c455a76-4b36-481c-9fc1-7af3b9df3d63)

Click Ok, and save the data pressing again Ok.

If you have some problems and you want to help me to investigate, check TraceOn as in the image.

### Timeout
Since everyone got it's own wifi, I added a time out selection (default is 5 minutes), if the driver can't reach the weather station after that time will close the connection with the software.


## Usage

Connect the equipment et voilà:

![image](https://github.com/user-attachments/assets/6337e953-e7c5-4cb2-a60d-c83980584435)



