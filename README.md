# DroneFace
An Open Dataset for Testing Face Recognition on Drones

# Download Link
[Download DroneFace](http://deal1.iecs.fcu.edu.tw/DroneFace.zip)

# Contents
DroneFace contains following contents:

* 11 subjects including 7 males and 4 females.

* 2,057 pictures including 620 raw images, 1,364 frontal face
images, and 73 portrait images

* The raw images are taken in 3,680x2,760 resolution with
ultra-wide field of view (170◦) under daylights.

* The resolutions of the facial images are between 23x31 and
384x384.

* The raw images are taken from 1.5, 3, 4, and 5 meters high.

* The raw images are taken 2 to 17 meters away from the
subjects with 0.5 meters interval.
* The 3-direction portrait images are taken by sport and
phone camera for comparison.


# Description
All the images in DroneFace are named in the following manner:

**subjectID_cameraType_heightID_imageType_distanceID.jpg**

*subjectID [[a-k]|ab|cd|ef|gh|ijk]*

*cameraType [gp|cam|na]*

*heightID [0|3|4|5|na]*

*imageType [eo|ef|por|por[F|L|R]*

*distanceID [00-30|na]*


11 subjects are named with English letters, a to k. The subject a,
b, c, e, g, j, and k are males, and the remainders are females. If the
subjectID part contains merely one letter means only one subject
is in the image; on the other hand, there are multiple ones. The
code "gp" in cameraType means the picture is taken using our sport
camera (GoPro Hero3+ Silver Edition), and "cam" indicates that the
pictures is taken using the HTC One M8 smart phone. heightID 0,
3, 4, and 5 represents that the camera is 1.5, 3, 4, and 5 meters high
from the ground accordingly while the picture is taken. imageType
"eo" means that the picture is a raw image, "ef" means thay the
image is a frontal facial image extracted from a raw image, "por"
means that the picture is the portrait handed by the subject, and
"porF", "porL", or "porR" means the pictures is the portrait images
of the subjects’ front, left, or right faces. The distance ID is a two
digit number, and the actual distance from the subject to the camera
equals to 17-(distanceID/2) meters. For any of the components in
the filename, "na" represents that the corresponding information is
not available.

# Reference
[1] Hwai-Jung Hsu and Kuan-Ta Chen. 2015. Face Recognition on Drones: Issues and Limitations. In Proceedings of the First Workshop on Micro Aerial Vehicle Networks, Systems, and Applications for Civilian Use (DroNet '15). ACM, New York, NY, USA, 39-44. DOI=http://dx.doi.org/10.1145/2750675.2750679
[2] Hwai-Jung Hsu and Kuan-Ta Chen. 2017. DroneFace: An Open Dataset for Drone Research. In Proceedings of the 8th ACM on Multimedia Systems Conference (MMSys'17). ACM, New York, NY, USA, 187-192. DOI: https://doi.org/10.1145/3083187.3083214
