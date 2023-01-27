---
title: "Interrater reliability test with EasyDIAG"
layout: single
permalink: /irr-test/
sidebar:
    nav: "docs"
---

From your annotated files, you can assess inter-rater agreement between 2 coders by analyzing a combination of both presence and duration of specific annotations, directly from your Elan coded file by using the EasyDIAg software package (Holle and Rein, 2015). The software allows to assess the agreement of raters in ELAN by detecting whether the raters agreed on an annotation value and duration. To reach agreement, the annotation values have to be identical and the duration has to overlap by at least 60%. The reliability agreement is thus based on a combined measure of annotation value and duration. 

To do so you first need to:
  * The annotations from the two raters should be contained in the same annotation file.
  * The tier names corresponding to the variables that will be evaluated for agreement rate must contain the indicators R1 for the first rater and R2 (e.g., ID_1_gesture_R1 and ID_1_gesture_R2). If these indicators are not specified in the tier names, EasyDIAG will not able to determine which annotations belong to which rater. 
  * Create a text file from your annotated file (see section 2.2.4.)
  * Only ‘include file name column’, ‘Begin time’, ‘End time’ and ‘msec’ should be ticked, everything else should be unticked. Indeed, the EasyDIAg toolbox expects a tab-delimited text file where the first column specifies the tier, the second and third columns the beginning and the end of the annotation (in msec), the fourth column the annotation category, and the last fifth column the file name (that specifies the rater ID). Tier names (in column 1) must contain the indicators R1 for the first rater and R2 for the second rater! If these indicators are not contained in the tier names the toolbox is not able to determine which annotations belong to which annotator. The order is not important but should be consistent throughout the files which ELAN takes care of. 
  
For further instructions, please refer to the EasyDIAG tutorial.