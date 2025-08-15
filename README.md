# OpenCamera-for-CRB-surveys
Documents use of the Open Camera Android app for data acquisition in automated roadside surveys of coconut rhinoceros beetle damage.
## Install and Configure the Open Camera app
* Open Google Playstore on your Android smartphone and install or update to the latest version of the Open Camera app (currently v1.54.1).
* Copy the configuration file from this repo into the Open Camera backups folder on your smartphone.
  * Download the latest configuration file (currently ```crb20250816.xml```) to your local computer.
  * Connect your smartphone to your local computer with a data cable.
  * Copy the configuaration file from your local computer to the Open Camera ```backups``` folder on your smartphone. On my phone, the backups folder is located at ```/Android/data/net.sourceforge.opencamera/files/backups/```.
  * Disconnet your smartphone from the local computer.
* Configure the Open Camera app on your smartphone  
  * Activate the Open Camera app.
  * Click on the gear icon, scroll to the bottom of the page and open the ```Settings Manager```.
  * Click on ```restore Settings```
  * Select the latest configuration file (currently ```crb20250816.xml```).

 Your Open Camera app should now behave as follows:
 * Images will be recorded with these parameters:
   * recorded at a rate of one image per second
   * saved in JPEG (*.jpg) format at a resolution of 1920 x 1080 pixels
   * saved in the ```/DCIM/crb``` folder with file names like ```20250816_051843.jpg```. File names include the local date and time.
     
Recording sessions can be started and paused by pressing the large blue circle on the Open Camera screen.
I recommended copying the contents of the ```/DCIM/crb``` folder to a local computer soon after completing a recording session.
After successfully copying the data, I recommend that you delete the ```crb``` folder from the smartphone. 
This folder will be automatically recreated the next time you start when Open Camera. 
