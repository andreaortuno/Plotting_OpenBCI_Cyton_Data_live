# Plotting live data from Cyton Board using Python

This is a very simple way for people starting with the OpenBCI Cyton board to play around with plotting data using the OpenBCI Python repo.


## Notes:
1. This notebook is being run on a Windonws 10 Laptop, using a Python3 environment. This notebook was also tested on a Linux VM.
2. After you installed all the [dependencies](http://docs.openbci.com/OpenBCI%20Software/05-OpenBCI_Python) correctly you can start using this tutorial.
3. This notebook was also tested on a Linux VM. To make it work make sure to also install [bluepy](https://github.com/IanHarvey/bluepy) as part of the requirements. Also change the port name to '/dev/ttyUSB*/'.

### Importing necessary packages:
The packages used for this tutorial are in the [requirements.txt](https://github.com/andreaortuno/Plotting_OpenBCI_Cyton_Data_live/blob/master/requirements.txt) file. You can simply download that file and install the requirements by typing "pip install -r requirements.txt" on the command line.

If you are having trouble with the plugin_interface you might need to use [this workaround](https://github.com/OpenBCI/OpenBCI_Python/issues/91#issuecomment-412817422).

### What you should see:

At the end of this tutorial you should be able to get the OpenBCI data and plot it live like the image below. The tutorial is meant to help you understand how to use the OpenBCI-Python repo, so if you have any questions feel free to open and issue.

![EEG image](https://i.ibb.co/9vRRMpP/EEG-plot.jpg)
