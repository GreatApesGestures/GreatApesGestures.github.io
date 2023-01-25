---
title: "Create annotations"
layout: single
permalink: /create-annotations/
sidebar:
    nav: "docs"
---

An **annotation** is any type of text (e.g., a speech transcription, a translation, a value, etc.) that you assign to a time **segment** (time interval of the media file) created in a tier (e.g., “Reach” in the “ID_2_Gesture” tier)


## Working modes

There are several working modes available to create annotations, but in most cases you will only need to use the annotation and segmentation modes to annotate your media file.

  * **Segmentation mode**: designed for rapid and easy creation of empty annotations while the media is playing <br><br>
  In this mode, there are several segmentation options (ways to create time intervals in your tiers)

      * <ins>“two keystrokes per annotation”</ins> for non-adjacent annotations (press “enter” once to create 1st boundary of the segment and press “enter” a second time to create the 2nd boundary of the segment) 

      * <ins>“one keystroke per annotation”</ins> for adjacent annotations (press “enter” once to create the 1st boundary of the segment and press “enter” a second time to create 2nd boundary of the segment, which is also the 1st boundary of the next segment)

      * <ins>“one keystroke per annotation”</ins>, fixed duration (here choose if the key stroke “enter” marks the beginning or the end of a fixed-duration segment.  Press “enter” once to create a fixed-duration segment, e.g., 3 sec segment)<br><br>

    To _adjust_ the boundaries of a created segment: it is possible to adjust the boundaries of a created segment by dragging it with the mouse to extend or shrink it (it needs to be selected by placing the mouse on it, and it becomes green).

    To _delete_ a created segment: it is possible to delete a created segment by selecting it (it becomes green) and pressing the back key to delete it.

  * **Annotation mode**:  generic mode in which almost all functions are available <br><br>
  In this mode, you can create time intervals (segments) by using the <ins>selection mode</ins>, or simply annotate already created intervals in the segmentation mode. <br><br>
  To _adjust_ the boundaries of a created segment: you cannot adjust the boundaries in this mode, to do so you have to switch to the Segmentation mode (see above section. <br><br>
  To _delete_ a created segment: you can remove a segment by selecting it (it becomes blue), then go to the menu <ins>Annotation</ins> > <ins>Delete annotation</ins>.   <br><br>
  To _delete_ an annotation value: you can remove the content of an annotation. To do so, select the annotation, go to the menu <ins>Annotation</ins> >  <ins>Remove annotation value</ins>


## Create segments (time intervals)

To create **time intervals** (segments) corresponding to the occurrence of an event you wish to annotate from your media file (e.g., the occurrence of a gesture), use the Segmentation mode 

  * Go to Option > Segmentation mode
  
![alt text](/assets/images/Segment.png)

  * Select segmentation option, for instance, “two keystrokes per annotation”

![alt text](/assets/images/Segment 2.png)
  
  or  “one keystroke per annotation”, fixed duration

![alt text](/assets/images/Segment 1.png)

  * Select the Tier you wish to add segments to by double clicking on it (it becomes highlighted in pink, with the name in red font) > start creating segments (time intervals) in the selected tier

## Create annotations


To create **annotations** within already created time intervals (segments created in the Segmentation mode) use the Annotation mode

  * Go to Option > Annotation mode

![alt text](/assets/images/segment 3.png)

  * Select the segment to annotate by double-cliking on it,  a little window opens. If you have created a CV for this tier, the list of possible values will appear and you can click on your selection

![alt text](/assets/images/annotation 2.png)
  
  If you haven‘t created a CV for this tier, you can directly type the value in the window

![alt text](/assets/images/Figure 21.png)

To create **annotations** without already existing segments

  * Go to Option > Annotation mode

![alt text](/assets/images/segment 3.png)

  * Select the „Selection mode“> Select the time interval by first clicking at the beginning of the time interval then dragging to highlight the selected time  interval (it becomes highlighted in blue). 

![alt text](/assets/images/Figure 20.png)

## Create annotations from overlapping annotations 

You can automatically create annotations from overlapping segments from different tiers (e.g., for Mutual gaze presence= overlap segment between ID_1_gaze orientation and ID_2_gaze orientation segments) 


  * Go to Menu Tier > create annotation from overlaps

![alt text](/assets/images/Overlaps 1.png)

  * Use currently opened file

![alt text](/assets/images/overlaps 2.png)
  
  * Select tiers to use for computation (e.g.; for Mutual gaze, ID_1_gaze orientation and ID_2_gaze orientation).


![alt text](/assets/images/overlaps 3.png)
![alt text](/assets/images/overlaps 4.png)
![alt text](/assets/images/overlaps 5.png)



