# Barcode Scanner

This project aims to incorporate the material discussed in the CSE483 course in a practical application, encouraging students to explore said material in practice and how to apply it in an actual problem they are facing, such as that of the captured image of a barcode to automatically scan the bars on the label emulating the behaviour of real-life barcode scanners. By preprocessing the captured barcode label image, an undistorted, noiseless, binarized (grayscale), clear barcode be obtained and decoded using [code 11 symbology](https://web.archive.org/web/20191201025306/http:/www.barcodeisland.com/code11.phtml).

The barcode decoding portion of the project may not be fully explored in the course material, however; it aims to expand the knowledge of students, and how they can apply their obtained knowledge on basics of classical computer vision to implement a real-life standard through simple logic; in this case that is to decode the position of pixels (representing the bars of the barcode) and their varying widths to decode the data represented in the barcode.

The final pipeline needs to be generic and robust enough, capable of passing as many test cases as possible without requiring any modifications or fine-tuning on-the-spot. In other words, if-conditions that attempt to figure out which test case is currently being processed are not considered generic. Your code should only try to figure out the problem(s) in the current test case (e.g., salt-and-pepper noise, rotated barcode, etc.) and apply the appropriate fix(es) when applicable.