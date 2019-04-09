+++
title = "CV Terminology"

date = 2019-04-09T00:00:00
# lastmod = 2018-09-09T00:00:00

draft = false  # Is this a draft? true/false
toc = true  # Show table of contents? true/false
type = "docs"  # Do not modify.

# Add menu entry to sidebar.
linktitle = "CV Terminology"
[menu.tutorial]
  parent = "Computer Vision"
  weight = 1
+++


## Keypoint

A keypoint is a point in the image which defines what is interesting or what stands out in the image. It can be considred as "an interesting point". It is special since it is supposed to be invariant to rotation, expansion, translation, etc.

## Descriptor

A decriptor is a finite vector and it summarizes propoerties for the keybpoint. Generally, it assigns a numerical description to the area of the image the keypoint refers to. It has to be independent of keypoint position, reliable against image transformations, and scale independent. After calculating descriptors for all the keypoints, you can compare the descriptors to find matchings from the keypoints.

## Feature
A feature is defined by a keypoint and descriptor.


### References
* [Stack overflow](https://stackoverflow.com/questions/29133085/what-are-keypoints-in-image-processing)
* [Univ. of Auckland](https://www.cs.auckland.ac.nz/~rklette/CCV-Dalian/pdfs/E02_Features.pdf)
* [Stack exchange](https://dsp.stackexchange.com/questions/10423/why-do-we-use-keypoint-descriptors)
