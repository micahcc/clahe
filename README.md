# CLAHE
📊 Contrast Limited Adaptive Histogram Equalization

👽 When maximum pixel value of the input image is smaller than u16::MAX, output would be different from OpenCV.

⚠️ Lots of `unsafe` code was used since safe version was slower than unsafe version (current implementation).