# License-Plate-Character-Segmentation

License plate character segmentation (including new energy license plate recognition)

Implementation: python + opencv

Main steps:
1. read the picture, and do grayscale processing.
2. Binary the grayscale image.
3. Split characters.
4. Cycle through the sum of black and white pixels for each column.
5. Split the image, given the starting point of the character to be split.
