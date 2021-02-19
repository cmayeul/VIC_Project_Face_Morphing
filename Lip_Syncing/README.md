# Image morphing and applications

VIC final project february 2021

## Visual lip syncing

To modify video_target with the mouth shape and moves from video_ref and save the result in video_out run : 

`python3 lip_sync.py video_target video_ref videoout`


You can do the same with an image as input one. The result is an animated image (only the mouth is animated) : 

`python3 lip_sync.py img_target video_ref video_out`


It is also possible to just modify the mouth shape of the character in img_target from a reference image. In this case the result is an image too : 

`python3 lip_sync.py img_target img_ref img_out`

## Reference

Parts from the code come from 

[https://github.com/Azmarie/Face-Morphing/tree/c8404c2a229b32ae3370848f556fa9d4af01f2a6](https://github.com/Azmarie/Face-Morphing/tree/c8404c2a229b32ae3370848f556fa9d4af01f2a6)
