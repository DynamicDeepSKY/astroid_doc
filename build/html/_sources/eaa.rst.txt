.. _eaa:

EAA Stacker
===========

EAA stacker will assist you to easily stack images and make a great visualization of deep sky object either with your existing telescope or the basic sky recognition lens (5mm).

What is Image Stacking?
-----------------------

The raw images from an image sensor are usually quite noisy. One of the simplest ways to handle such noise is to take multiple images and getting an averaged image. EAA stacker supports multiple useful tools for image stacking.

Exposure Time and Gain
------------------------
Exposure time and gain can be adjusted according to your preference. Short exposure time enables the EAA stacker to be more responsive to the mount movement and creates a less blurry image when used with a longer focal length lens. Long exposure can reduce image noise but it can cause unwanted star trails especially on manual and Altazimuth mounts.

Adjusting the gain to a higher value will amplify some faint signal such as nebular and make it more visible while it increases noises on the image. 160 or lower is recommended for the gain. When there is too much noise due to the high gain value, increasing the stacking image number will lower the overall noise level.  




Installation Example
---------------------

Astroid comes with a 50.0mm camera tube and 1.25-inch female thread for connectivity with the most common connection standards. The following example shows how you can use these two to mount Astroid to your telescope lens.


To use Astroid, the 5mm lens should be removed. The figure on the left shows standard telescope adaptors and lens that can be used with Astroid.

.. figure:: /images/adaptors.jpg
   :width: 400
   :alt: Adaptors
   :align: center

If your telescope only has a 1.25-inch eyepiece mount, use a 1.25-inch male-to-female adaptor to be able to mount Astroid on your telescope. The following shows an example configuration with Celestron's 1.25-inch adaptor.

.. figure:: /images/125_inch_adaptor.jpg
   :width: 400
   :alt: 1.25inch
   :align: center

In case your telescope has a 2-inch adaptor you do not need to separately buy a 1.25-inch tube instead you can directly insert Astroid into a 2-inch adaptor.
    
.. figure:: /images/2_inch_adaptor.jpg
   :width: 400
   :alt: 2inch
   :align: center

A bright DSLR lens such as Samyang(Rokinon) 85mm F1.4 or 135mm F2.0 lens also makes a great result with Astroid. Please note that mirrorless lenses such as the sony E-Mount lens are not suitable for Astroid due to the focal length. Canon EF mount lens is highly recommended.
   
.. figure:: /images/Sony_emount.jpg
   :width: 400
   :alt: dslr
   :align: center
      





Stack Mode
------------
EAA Stacker supports two stack modes: with and without tracking. The tracking mode automatically aligns input images to the first image that was captured when the live stack mode was turned on. This is especially useful on a manual mount and an Altazimuth mount as the outcome looks like a static view. Turning off the tracking mode will be required when the lens is dark and the EAA stacker does not find a star to track. For example, any lens above F5 might cause frequent tracking reset due to a lack of trackable stars in the image. You can adjust the gain to make the stars are visible enough for tracking. You can also turn off the tracking mode will let the EAA stacker simply average images without alignment. Note that when the tracking option is off you must turn on the physical tracking option on your mount.

Mean Substraction
------------------
If the stacked image is too bright check this option. This option estimates the mean RGB value of the stacked image and subtracts it. Use this option if you are using EAA stacker under the sky with light pollution.


Tone Curve
-----------
EAA stacker provides a basic tone curve interface to effortlessly give a dramatic change to the raw image. Check the ToneCurve option in the control panel to show the tone curve and add multiple control points to adjust the curve. Typically to amplify the lower side signal the curve should sharply increase around the lower side and gradually on the high side like the following image. 

.. figure:: /images/tonecurve.png
   :alt: Tone Curve
   :align: center
   
To make such a tone curve you need to add two control points by clicking the curve line. Check the ApplyToneCurve option to apply the tone curve.

      

Stacking Number
----------------

The number of images to be stacked can be adjusted through this option. The stacking numbers 4, 8, 16 add all the images on the buffer and divide by each stacking number whereas 32, 64 add without division for a darker lens.

