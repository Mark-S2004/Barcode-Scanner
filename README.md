# Barcode Scanner

This project aims to incorporate the material discussed in the CSE483 course in a practical application, encouraging students to explore said material in practice and how to apply it in an actual problem they are facing, such as that of the captured image of a barcode to automatically scan the bars on the label emulating the behaviour of real-life barcode scanners. By preprocessing the captured barcode label image, an undistorted, noiseless, binarized (grayscale), clear barcode be obtained and decoded using [code 11 symbology](https://web.archive.org/web/20191201025306/http:/www.barcodeisland.com/code11.phtml).

The barcode decoding portion of the project may not be fully explored in the course material, however; it aims to expand the knowledge of students, and how they can apply their obtained knowledge on basics of classical computer vision to implement a real-life standard through simple logic; in this case that is to decode the position of pixels (representing the bars of the barcode) and their varying widths to decode the data represented in the barcode.

The final pipeline needs to be generic and robust enough, capable of passing as many test cases as possible without requiring any modifications or fine-tuning on-the-spot. In other words, if-conditions that attempt to figure out which test case is currently being processed are not considered generic. Your code should only try to figure out the problem(s) in the current test case (e.g., salt-and-pepper noise, rotated barcode, etc.) and apply the appropriate fix(es) when applicable.

## Preprocessing pipeline results

![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/01%20-%20lol%20easy.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/02%20-%20still%20easy.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/03%20-%20eda%20ya3am%20ew3a%20soba3ak%20mathazarsh.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/04%20-%20fen%20el%20nadara.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/05%20-%20meen%20taffa%20el%20nour!!!.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/06%20-%20meen%20fata7%20el%20nour%20333eenaaayy.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/07%20-%20mal7%20w%20felfel.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/08%20-%20compresso%20espresso.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/09%20-%20e3del%20el%20soora%20ya3ammm.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/10%20-%20wen%20el%20kontraastttt.jpg.gif)
![](https://github.com/Mark-S2004/Barcode-Scanner/blob/main/gif/11%20-%20bayza%205ales%20di%20bsara7a.jpg.gif)
