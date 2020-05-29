# Deep Image Reconstruction: Questions and aswers

## How can I get stimulus images?

We do not include stimulus image files in the open dataset because of license issues.
Please contact us via [email](mailto:kamitanilab@gmail.com) for sharing the image files.

## How can I get field maps for distortion correction in the fMRI data?

We did not collect field maps during the fMRI experiments (so we did not apply distortion correction on EPI images in the original analysis).
[fmriprep](https://github.com/poldracklab/fmriprep) provides distortion correction without field maps and it can be used for EPI distortion correction on our data, although we haven't tried it by ourselves.
