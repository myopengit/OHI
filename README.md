# OHI

Online Human Interaction (OHI) Database

This database contains total 10 human interactions: shaking hands, high waving, kicking, punching, pushing, hugging, high-fiving, approaching, departing and exchanging objects. Each interaction is performed by 23 pairs of subjects for 2 to 4 times. 
We record RGB images (640*480), depth images (640*480), and 3D coordinates of 20 skeleton joints for each pair of subjects using Kinect version 1. The registered depth images are also provided for the facility of fusing the information from both channels at the pixel level. 

There are two parts in this database.

In Part I, segmented data is provided for the evaluation of offline activity recognition. Interactions are divided into isolated sequences according to interaction categories. The skeleton data is available in current version. 
Please find the details in OHI_Seg_Data

In Part II, continuous video streams are collected for the evaluation of online activity recognition methods. Each video sequence contains 10 human interactions continuously performed by one pair of subjects. The ground truth labels along with the starting and ending points of activities are provided. During the interval of two activities, the subjects are free to perform any actions instead of standing still, which makes this database closer to practical scenarios as well as challenging. Figure 2 shows an example sequence of our database. 
The RGB videos and corresponding depth videos and skeleton sequences can been find in OHI_Continuouse_Data

