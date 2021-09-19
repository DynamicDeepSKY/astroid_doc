.. _quickstart:

Quick Start Guide
=================

Start Astroid
-------------

1. Connect Astroid to a USB power. Make sure to use a stable power source that has at least 5V 3A capacity. 
2. Open up your wifi setup in your mobile device or desktop and find DDS\_DIRECT. Password is 12345678
3. Open your web browser and type 10.10.10.10 or astroid.local 

.. figure:: /images/ip_address.png
   :alt: IP address
   :align: center

4. You should see the rotating logo soon

.. figure:: /images/rotating_logo.png
   :width: 400
   :alt: Rotating logo
   :align: center



Lens Mount
-------------

**eFinder** and **Dr. Pole** requires provided 5mm lens to be mounted. When mounting the lens to Astroid, the lens should be carefully placed otherwise the plastic thread on the camera will be destroid and cannot be used. See the following instruction.

.. figure:: /images/lens_mnt.png
   :width: 400
   :alt: Lens mount
   :align: center
   



eFinder 
-----------

This feature of Astroid completely substitutes the conventional dot finder or finder scope. With the built-in sensor and the basic lens, you can use Astroid as an electronic finder. Astroid's eFinder does not just show you sky image but can tell you what are you looking at and guide you to the sky objects you would like to see.

To use Astroid as eFinder, you need a camera holder. You can either 3D print it or an aluminum version will be available soon.

Follow the procedure below to use eFinder.

1. Mount the holder to your telescope.  
2. Slide Astroid camera into the holder. If you are using 3D printed version, make sure the back side is firmly hold by the holder. 
3. Rotate the lens to adjust focus if it is the first time. Set exposure to 0.3 second and exposure to 150 for fast focusing
4. If it is the first time to use or the location you use Astroid is far away from the last location, update the long and lat under Astro Tools menu. If you don't know your long and lat, go to google map and see what is your long and lat. *This manual GPS input will be changed to automatic in the next update.*

.. figure:: /images/gps_google_maps.png
   :alt: GPS location from google maps
   :align: center

5. Click the eye button |liveps| to start live sky recognition. 

.. |liveps| image:: /images/liveps.png
                :scale: 10 %


6. Align Astroid to main telescope lens. To show the alignment joystick go to Astro Tools and check FinderAlign.  

.. figure:: /images/finderalign.png
   :width: 400
   :alt: Finder align 
   :align: center


7. Touch the finder icon on the buttom side and search any object you want to find by typing a star ID

.. figure:: /images/finder.png
   :width: 400
   :alt: Finder align 
   :align: center

8. Red target mark is what your main lens is looking at and green mark is what you need to go.

.. figure:: /images/search_guideline.png
   :width: 400
   :alt: Guide line
   :align: center




.. list-table:: example longitude and lattitude
   :align: center
   :widths: 25 25 50
   :header-rows: 1
   

   * - Location
     - long
     - lat
   * - Australia Brisbane
     - 152.887277
     - -28.030904 
   * - Korea
     - 127.667991
     - 36.664273
   * - New Zealand
     - 174.807480
     -  -36.866884
   * - Italy milano
     - 9.184879
     - 45.466708 
   * - US Kansas  
     - -98.139525 
     -  38.396799 
   * - Japan
     - 140.002557
     - 35.736418


.. admonition:: Tips

    Once the sky is recognized, move your mount slowly so that Astroid does not lose the recognized stars. Once it lost the stars, it will take about 2~5 seconds to recover.
    
    
   
eFinder Align
-------------

If you would like to use astroid as a finder, you have to align Astroid to your main telescope view just like what you do with a conventional finder scope but in a digital way. Follow the procedure below to align Astroid to your main lens.


.. admonition:: Important

    The first alignment is highly recommended to be done in the sunset rather than a dark night. If you have a bright object like a street light around your telescope, the alignment can be done at night too.   

1. Adjust your telescope to put a bright and distinctive object in the center of the eyepiece. Street light or window light is useful for this. Starlight is not recommended as it is not very distinctive and moving.
2. Press the eye button |liveps| to start sky recognition mode. 
3. Press the setup button |toolbt| to open the setup panel.

.. |toolbt| image:: /images/bbtSettings-on.png
   :scale: 40 %
   
4. Open "Astro Tools" menu and check the following four options.

.. figure:: /images/align_setup.png
   :alt: Align setup
   :align: center
   
5. Identify the location of the bright object in the image
6. Adjust the joystick to move the red target mark toward the object  


.. figure:: /images/target_mark.png
   :alt: Target mark
   :align: center   
   
   Target mark
   
.. figure:: /images/joystick_img.png
   :alt: Joystick Image
   :align: center   
   
   Joystick
   
7. Unchecking the FinderAlign will automatically save the current location so that you do not need to do the align next time. 






EAA Stacker
---------------

Electronically Assisted Astronomy (EAA) stacker offers a set of tools that make the live stacking and registration super easy. You can use this feature either for the basic lens, DLSR lens, or telescope. When the stacker is used with the basic lens, it will show the clear shape of the Milkyway which is often very useful to know the location of your interested sky object with respect to the Milkyway. DSLR lens or telescope lens can be mounted on Astroid after removing the basic lens. When EAA stacker is used with these two types of lens, it will give you a much brighter image of the sky object than observing them with your bare eye.

Follow the procedure below to use EAA stacker with DSLR lens or telescope lens. 

1. Slide the camera into 2 inch scope eyepiece holder. Optionally you can purchase 1.25 inch extension tube and connect it to Astroid to slide it into a eyepiece hole.
2. Set exposure to 0.3 second and gain to 150 for fast focusing
3. Adjust your telescope's focus knob and see any star appears on the screen. Finding the right focus could be an extream job if you do it at night. Do it when it is not too dark and leave a mark around your telescope focuser so that you can easily set the focus to near position.  
4. Click the stack icon on the bottom right corner to start the image stacking.
5. Stacking will show the best result if F number is low e.g. F2.

Stacking result on Samyang 85mm@F2. 

.. figure:: /images/stacker85mm.png
   :width: 400
   :alt: Stacker 85mm
   :align: center  


To use the EAA stacker with the basic lens, just activate click the stack icon. Adjusting tone curve and lowering CurveHigh value will make the image even better like the following example.  

.. figure:: /images/stacker5mm_onoff.png
   :width: 400
   :alt: Stacker
   :align: center  

When stacking is enabled in eFinder mode, the stacked image will be aligned to the sky. You can enable eFinder features such as displaying a constellation as shown in the following example.

.. figure:: /images/stacker_const.png
   :width: 400
   :alt: Stacker
   :align: center  

Dr. Pole
---------------

Dr. Pole is a standalone polar alignment assistant tool for EQ mounts. Compared to the existing solution, Dr. Pole does not require the pole star to be within the camera view which makes the polar alignment much easier when you are in the Southern hemisphere or when the pole star is not visible around your place due to a tree or building.  

Follow the procedure below for the polar alignment.

1. Mount the holder to your telescope.  
2. Slide Astroid camera into the holder. If you are using 3D printed version, make sure the back side is firmly hold by the holder.

.. figure:: /images/eq_mnt.png
   :width: 400
   :alt: EQ mount
   :align: center

.. admonition:: Important

    Not like the other products, Astroid can be mounted on DEC axis or directly on lens. This gives you more flexibility when the pole star is not visible. You can mount Astroid on RA axis too. 


3. Rotate the lens to adjust focus if it is the first time. Set exposure to 0.3 second and exposure to 150 for fast focusing
4. Click the eye button to start live sky recognition. 
5. Click the telescope icon on the buttom right corner.
6. Move RA axis of the telescope to the first position (-30 degree) and wait until the sky is recognized
7. Press next button and move the RA axis again to 0 degree and repeat 6,7 for one more time. 
8. Once the he axis finder is normally finished, the rotation axis and the SCP or NCP will be displayed on the screen with a guide line.
9. Adjust your mount base according to the guide line


How to Turn Off Astroid
-----------------------

1. Go to System Setting 
2. Press PowerOff button
3. Wait for 10 seconds to be safe
4. Unplug the power

.. admonition:: Important

    If you cut the power without parking, sometime SD card is corrupted and you have to recover it to factory setup.
