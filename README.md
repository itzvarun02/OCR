
# Make the same changes in OpenOCRCorrect 

Assignment 3
## Features
Implimented the bold/unbold feature in OpenOCRCorrect.

## Installation

Install my-project with npm

```bash
  $ cd FrameWorkCode
  $ qmake qpadfinal.pro
  $ make
```
For running the code
```bash
$ ./qpadfinal
```
ignore error
## Issues/challenges

1. Unable to Add the subscript and superscript functionality to the above software
2. Lot of Build Error...
3. Subscript and superscript tags belong to supported HTML subset so one can use them in all the widgets (like QLabel and QTextEdit) that support rich text. However, QListWidget and QLineEdit do not support rich text. One can enable rich text support in model-view classes by a custom delegate like this.
4. QLineEdit wasn't really made for superscript and subscript functionality type of thing, as it was designed for simple text entry.


##  Reference

This Project was taken from https://github.com/rohitsaluja22/OpenOCRCorrect.git

