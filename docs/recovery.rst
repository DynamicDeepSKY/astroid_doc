.. _recovery:

Recovery Instruction
====================

Before you start the recovery process you have to backup your license and calibration files. 

1. Download your license file

.. figure:: /images/license_download.png
   :width: 400
   :alt: License Download
   :align: center
   
2. Download your lens calibration file

.. figure:: /images/calibration_download.png
   :width: 400
   :alt: Calibration Download
   :align: center
   
If your device does not boot and cannot download these files please contact us at info@dynamicdeepsky.com. We will send you those files as soon as possible.
   
Follow the steps below to recover your device to the factory setup.

1. Download the Astroid OS image from dynamicdeepsky.com under the support page 
2. Download the Raspberry pi imager from https://www.raspberrypi.org/software/
3. Pull out the OS SD card from Astroid and mount it to your computer either by SD card USB adaptor or built-in sd card reader.
4. Burn your SD card with the downloaded image.
5. Put it back to Astroid and connect the power.
6. Wait for 5~10 minutes until you see "RPiHotspot" in the WIFI list.

.. admonition:: Important

	If you cut the power before you see "RPiHotspot", you have to start from 3 again.
    

7. Connect to RPiHotspot and set your serial by entering the following into the web browser:  

**http://10.10.10.10/setserial/YOUR_SERIALNUMBER**

For example, if your serial number is 1030001 use the following command.

http://10.10.10.10/setserial/1030001

.. figure:: /images/set_serial.png
   :width: 400
   :alt: Set serial
   :align: center
   
Once you enter the serial number your device's WIFI ID will be changed to DDS_DIRECT_1030001

8. Now, you need to set up your license and serial. Click the"License Code File" button under "System Setting"->"License Management" and select the file you downloaded before the reset.

.. figure:: /images/license_upload.png
   :width: 400
   :alt: Calibration Upload
   :align: center

9. Click the "Load Calibration" button under "System Setting"->"Calibration" and select the file you downloaded before the reset.

.. figure:: /images/calibration_upload.png
   :width: 400
   :alt: Calibration Upload
   :align: center
   
10. Check the system version on the ShowInfo window and run update if it is outdated. See :ref:`System Update <systemupdate>` for more information
