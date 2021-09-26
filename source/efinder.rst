.. _efinder:

eFinder
=======
Pressing the eye button on the downside icon bar will automatically change Astroid to eFinder mode and activate live sky recognition. If you would like to use eFinder as a sky navigator, make sure the sky is recognized. The red eye icon on the status bar will turn into the green eye in case the sky is recognized. 

.. admonition:: Important

	Note that the sky recognition mode only works with the provided 5mm lens. You can mount other lenses to use Astroid as an electronic finder but the sky recognition would not work.
    
Sky Recognition
------------------------------------------------

When the sky recognition is activated, Astroid will try to recognize the sky but it might fail in some cases. If the sky recognition status icon does not turn green in 5 seconds try the following.

* Check if the lens focus is correct. With the blurry focus, Astroid does not recognize stars well.
* Make sure there are enough stars in the image. 
* Adjust the Gain a bit higher or lower. The image should not too bright or dark. Adjusting exposure to higher is not recommended as it slows down the response speed.
* Point the camera to a direction where no cloud, moon, the building exists. Usually, it takes more time to recognize the sky when there are obstacles in the view. Once it is recognized slowly move the camera in the desired direction.

Light Pollution
---------------------------------------------------

One of the dominant factors that control sky recognition performance is the sky condition. The best sky condition would be a very dark sky under Bortle 6 without the moonlight. Bortle is a metric to estimate the amount of light pollution in the night sky. You can easily see the Bortle level of your place from the following site.

https://www.lightpollutionmap.info/

The following example shows the Bortle level of three different places around Brisbane city.

.. figure:: /images/bortle.png
   :width: 600
   :alt: Bortle
   :align: center

The sky recognition performance is not guaranteed around the high light pollution area above Bortle 6. Refers to the following table for the details of Bortle class.


.. list-table:: Bortle Class
   :align: center
   :widths: 50 25
   :header-rows: 1   

   * - Sky Condition
     - Bortle Class
   * - Excellent dark sky
     - 1
   * - Average dark sky
     - 2
   * - Rural sky
     - 3
   * - Rural/Suburban transition
     - 4     
   * - Suburban
     - 5
   * - Bright suburban
     - 6
   * - Suburban/urban transition
     - 7
   * - City sky
     - 8     
   * - Inner city sky
     - 9        
        
     

    
Sky Recognition with Moon Light or Light Pollution
---------------------------------------------------

Although it is recommended to be used under Bortle 6 and without the moonlight, if you can't avoid such an environment there is a trick that you can do to make eFinder works but with limited speed and accuracy.

The default setting of sky recognition is 0.3 sec for the exposure and 140 for the gain which is optimized for Bortle 5 without the moonlight. The low exposure helps to increase response speed but needs a high gain setup which results in a noisy image under light pollution and the moonlight condition. Noisy image decreases the sky recognition performance.   


The simple solution is compromising the response speed by increasing exposure and lowering the gain. The following example shows how the exposure and the gain setup reduces noise moonlight conditions.  

.. figure:: /images/light_condition_low_exposure.png
   :width: 400
   :alt: Low exposure
   :align: center   
   
.. figure:: /images/light_condition_max_exposure.png
   :width: 400
   :alt: Max exposure
   :align: center




Geolocation and Time
------------------------------------------------

System time is automatically updated according to your device's time but you have to put long and lat information manually. Initially, these are set to 0 and you will see the red GPS icon on the top status icon location. Time and GPS information are important to properly draw the predicted sky.

After setting your GPS location, it is a good idea to double-check it with other software such as stellarium-web.org. Check if the four cardinal directions and the location of the Milkyway is identical on both sides. 

Marker
------------------

As soon as you activate eFinder mode you will see a red mark on the image. The center of the red circle is where your main telescope is looking at. If it is the first time to use this feature with your telescope, you might need to move this mark a little bit to make it aligned with your telescope's view. Refers to :ref:`eFinder Align <quickstart>` for the detailed procedure.



Time Adjust
------------------

By default, the planetarium will show you the current sky. But you can draw the past and future sky by adjusting the time bar. The supported range is -10 to +10 hours to the current time.


Star Finder
------------------

Astroid has built-in NGC, IC, M, HIP star lists. To use the star finder, find the number of the star object that you are interested in and enter it into the search bar. It will show you its photo and other information as well.

Once you clicked any star on the star finder list, Astroid will display the location of the target and how many degrees you should rotate along with the left/right and up/down direction. Adjust your mount according to this angle. Currently, the EQ mount guideline is not supported but this feature will be added in the next update.


Camera Centric Mode
----------------------------------------

As a default, when you drag the screen it will always move around AzAlt direction. But sometimes it is convenient to fix the screen view to the camera view and move the world instead. Enable the CameraView option in the setting menu, if you would like to enable this feature. 

Constellations and Stars
-----------------------------------------------------

You can turn on/off the constellations, stars, and star names according to your preference. Enable desired options in the control panel.




Auto Center and FoV Mode
----------------------------------------------------

AutoCenter and AutoFoV mode automatically adjust the view so that you don't need to touch the phone screen and move the view while your hands are busy with adjusting your mount.
