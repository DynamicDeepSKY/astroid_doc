.. _efinder:

eFinder
=======

Clicking the eye button |liveps| on the downside icon bar will swith Astroid's operation mode to eFinder and activate live sky recognition. Before you use eFinder, make sure the sky is recognized. The red eye icon |eye_red| on the status bar will turn into the green eye |eye_green| when the sky is recognized. 

.. |liveps| image:: /images/liveps.png
                :scale: 30 %

.. |eye_green| image:: /images/eye_green.png
                :scale: 30 %
                
.. |eye_red| image:: /images/eye_red.png
                :scale: 30 %
                
.. admonition:: Important

	Note that the sky recognition mode only works with the provided 5mm lens. You can mount other lenses to use Astroid as a camera but the sky recognition would not work.
    
Sky Recognition
------------------------------------------------

When the sky recognition is activated, Astroid will try to recognize the sky but it might fail in some cases. If the sky recognition status icon does not turn to green in 5 seconds try the following.

* Check if the lens focus is correct. With the blurry focus, Astroid does not recognize stars well.
* Make sure there are enough stars in the image. 
* Adjust the gain/exposure a bit higher or lower. The image should not too bright or dark. Note that adjusting exposure to higher slows down the response speed.
* Point the camera to a direction where no cloud, moon, the building exists. Usually, it takes more time to recognize the sky when there are obstacles in the view. Once it is recognized slowly move the camera in the desired direction.

Light Pollution
---------------------------------------------------

One of the dominant factors that affect sky recognition performance is the sky condition. The best sky condition would be a very dark sky under Bortle 6 without the moonlight. Bortle is a metric to estimate the amount of light pollution in the night sky. You can easily see the Bortle level of your place from the following site.

https://www.lightpollutionmap.info/

The following example shows the Bortle level of three different places around Brisbane city.

.. figure:: /images/bortle.png
   :width: 600
   :alt: Bortle
   :align: center

Although it might work, the sky recognition performance is not guaranteed around the high light pollution area above Bortle 6. Refers to the following table for the details of Bortle class.


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


A simple solution is compromising the response speed by increasing exposure and lowering the gain. The following example shows how the exposure and the gain setup reduces noise moonlight conditions.  

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

System time is automatically updated according to your device's time but you have to put longitude and lattitude information manually. Initially, these are set to 0 and you will see the red GPS icon on the top status icon location. Time and GPS information are important to properly draw the predicted sky.


Marker
------------------

As soon as you activate eFinder mode you will see a red mark on the image. The center of the red circle is where your main telescope is looking at. If it is the first time to use this feature with your telescope, you might need to move this marker to make it aligned with your telescope's view. Refers to :ref:`eFinder Align <quickstart>` for the detailed procedure.



Time Adjust
------------------

By default, the planetarium will show you the current sky. But you can draw the past and future sky by adjusting the time bar. The supported range is -10 to +10 hours to the current time.


Star Finder |search|
--------------------------------

.. |search| image:: /images/search.png
                :scale: 40 %


Astroid has built-in NGC, IC, M, HIP star lists. To use the star finder, find the number of the star object that you are interested in and enter it to the search bar. It will show you its photo and other information as well.

Once you clicked a star on the star finder list, Astroid will display the location of the target and how many degrees you should rotate along the left/right and up/down direction. Adjust your mount according to this angle. Currently, the EQ mount guideline is not supported but this feature will be added in the future update.


AR Mode |AR|
----------------------------------------

.. |AR| image:: /images/AR.png
                :scale: 10 %
                
As a default, when you drag the screen it will always move around AzAlt direction. But sometimes it is convenient to fix the screen view to the camera view and move the world instead. Enable the CameraView option in the setting menu, if you would like to enable this feature. 

Click and Find
-----------------------------------------------------

One of the most unique feature of Astroid is that you can click and find the star and DSO infromation from the camera's image. Combined with EAA stacker, Astroid provides visually interective way to explorer the night sky rather than just selecting a star on a list.



Camera Lock and Unlock |lock| 
----------------------------------------------------

.. |lock| image:: /images/lock.png
                :scale: 40 %

User interface automatically follows center of the camera image by default. If you would like to unlock the automatic camera follow mode, simply click the lock button on the left side |lock|.

Clicking the button one more time will switch it back to the lock mode and follow the camera. 




Star List |starlist2|
----------------------------------------------------

.. |starlist2| image:: /images/starlist.png
                :scale: 40 %
                
                
You can make your own star list by clicking add button |add_to_list| in the star finder window.

.. figure:: /images/searched_star.png
   :width: 200
   :alt: Max exposure
   :align: center

.. figure:: /images/auto_search.png
   :width: 400
   :alt: Max exposure
   :align: center



.. |add_to_list| image:: /images/add-list.png
                :scale: 40 %
                
                
The added stars can be seen on the star list window. Click |starlist| to open the star list window.



.. |starlist| image:: /images/starlist.png
                :scale: 40 %


Also, you can automatically search the nearby DSO to your current telescope and add it to the list by clicking |search_list| icon. 

|search_list| Search nearby DSO. By default M is used but you can change it to NGC, IC in the Astro tools menu.

.. |search_list| image:: /images/search_list.png
                :scale: 40 %

To save and load the star list use the following icons.

|save_list| Save list. The list is stored on Astroid's internal memory.

.. |save_list| image:: /images/save_list.png
                :scale: 40 %
                

|download_list| Load list. 

.. |download_list| image:: /images/download_list.png
                :scale: 40 %






Automatic DSO search |autodso_search|
----------------------------------------------------

Enabling this will automatically find the nearest DSO to the current main telescope's view and display it on the screen.

.. |autodso_search| image:: /images/autodso_search.png
                :scale: 40 %
                
