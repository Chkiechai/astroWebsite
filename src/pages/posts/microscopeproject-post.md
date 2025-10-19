---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Microscope Camera Mount'
schoolRelated: true
pubDate: 2025-10-17
description: 'The desiging process and steps for how I created a camera mount for our microscope'
author: 'Briana Lee'
image:
    url: '/assets/MountMOUNTED.png'
    alt: '3D Rendering of a Cylindrical Object'
tags: ["blogging", "school"]
---
### About The Project

Status: Finished

#### Why It Was Needed

I created this camera mount because we needed a way to view and photograph living organisms with our microscope, and while we had a camera suitable for the task, we didn't have a way to secure it to the microscope safely. The camera itself, an RPICam GUI, is a very sensitive device that will be destroyed with any small amount of static shock, so it's very important to make sure it has a shield to protect it from our hands.

I had a very simple idea for how to accomplish this; design a cylinder in Onshape CAD and size it so it would fit around the microscope eyepiece securely. The camera would be mounted in the cylinder using heat set inserts, protected from falling out and being shocked.


#### The Process

The first step was to measure the components I would be using, so I strapped a grounded band to my wrist and set about making a simple model of the PICam. I measured its dimensions, width, height, and length, as well as the screws and placement of the camera and the other components. This was somewhat difficult, as the camera lens wasn't centered on the board and the screws were in odd positions. 

![RPICamGUI Camera](/assets/PICAM.png)
*The Simple Camera Model*

After I finished modeling the camera, I moved on to making the cylinder that would fit around the microscope eyepiece. For this, I didn't need to use the grounded wristband, so I was able to move unrestricted. I measured the exterior of the eyepiece and made that the interior size of my cylinder, then sketched another circle around the interior, spaced a few hundredths of an inch away from the interior, so that when I extruded the gap between the circles the resulting cylinder would be strong.

I extruded the cylinder to make it taller, then made a top piece that was inset from the interior of the cylinder, making sure the inset was the same width as the eyepiece's lens.

Then, I imported the camera model into my assembly and positioned it using fastened mates, making sure to center the camera lens. After that was finished, I measured the dimensions and extruded the top of the cylinder down until the camera would fit snugly into the slot. I also made a small rim around the camera for extra security.

![Mount From The Side](/assets/MountSIDE.png)

*The Mount From The Side (Above)*

![Mount From The Top](/public/assets/MountTOP.png)

*The Mount From The Top (Above)*

#### Results

##### Setbacks

When I printed my mount for the first time, I hadn't added the rim around the camera, and I hadn't chamfered the inside of the inset on the cylinder, leading to spaghetti noodling on the part of the PLA plastic, making the inside of the cylinder rough. My measurements were also *too* accurate, meaning the mount fit, but it was too snug of a fit and therefor unusable. The camera's fit was also too tight, and I had forgotten to add account for one of the components. We also discovered that for the camera to work effectively, it had to be a small distance away from the microscope eyepiece's lens.

##### Successes

Once I revised the mount, it worked much better. I added a few thousandths to my measurements, allowing some room for the PLA plastic to expand. I also offset the camera from the eyepiece lens, and added the rim, as well as heat set screw mounts.