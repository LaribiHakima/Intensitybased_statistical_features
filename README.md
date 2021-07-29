#  3D digital phantom

- Using the following 3D digital phantom and associated segmentation mask: https://github.com/theibsi/data_sets/tree/master/ibsi_1_digital_phantom.
- I computed : “Intensity-based statistical features” from the digital phantom using only the voxels defined by the segmentation mask (voxels with intensity 1).
  - The feature list and associated definitions was found in section 3.3 of the following document: https://arxiv.org/pdf/1612.07003.pdf
- The results are exported in a CSV file.
