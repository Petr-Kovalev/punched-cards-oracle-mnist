### 'Punched cards' for Oracle-MNIST

*Object recognition by sparse random binary data lookup. Based on [this article](https://petr-kovalev.medium.com/punched-cards-object-recognition-97523a98857b)*

Performing single-shot Oracle-MNIST ancient characters recognition by lookup over the most representative sparse input bit sets of the training data (out of 28⋅28⋅8 = 6272 bits per training sample)

Bit vector set similarity evaluation using the maximum spanning tree is described in [this article](https://petr-kovalev.medium.com/bit-vector-set-similarity-maximum-spanning-tree-2121b05c7b29)

The same algorithm applied to the QMNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-qmnist)

The same algorithm applied to the Fashion-MNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-fashion-mnist)

### Program output:
```
Punched card bit length: 8

Average single-shot correct recognitions on fine-tune iteration: 4580, 4560

Top punched card per input:
Training results: 4702 correct recognitions of 27222
Test results: 498 correct recognitions of 3000

Top 39 (5%) punched cards per input:
Training results: 7181 correct recognitions of 27222
Test results: 739 correct recognitions of 3000

All punched cards:
Training results: 8397 correct recognitions of 27222
Test results: 792 correct recognitions of 3000

Punched card bit length: 16

Average single-shot correct recognitions on fine-tune iteration: 4814, 4836, 4836, 4832

Top punched card per input:
Training results: 5624 correct recognitions of 27222
Test results: 568 correct recognitions of 3000

Top 19 (5%) punched cards per input:
Training results: 8346 correct recognitions of 27222
Test results: 844 correct recognitions of 3000

All punched cards:
Training results: 9687 correct recognitions of 27222
Test results: 947 correct recognitions of 3000

Punched card bit length: 32

Average single-shot correct recognitions on fine-tune iteration: 5295, 5384, 5418, 5434, 5443, 5447, 5446

Top punched card per input:
Training results: 6741 correct recognitions of 27222
Test results: 743 correct recognitions of 3000

Top 9 (5%) punched cards per input:
Training results: 9077 correct recognitions of 27222
Test results: 974 correct recognitions of 3000

All punched cards:
Training results: 10854 correct recognitions of 27222
Test results: 1065 correct recognitions of 3000

Punched card bit length: 64

Average single-shot correct recognitions on fine-tune iteration: 5883, 6030, 6090, 6117, 6135, 6146, 6152, 6154, 6156, 6155

Top punched card per input:
Training results: 7265 correct recognitions of 27222
Test results: 774 correct recognitions of 3000

Top 4 (5%) punched cards per input:
Training results: 8546 correct recognitions of 27222
Test results: 900 correct recognitions of 3000

All punched cards:
Training results: 11509 correct recognitions of 27222
Test results: 1111 correct recognitions of 3000

Punched card bit length: 128

Average single-shot correct recognitions on fine-tune iteration: 6568, 6711, 6777, 6818, 6841, 6858, 6866, 6877, 6882, 6886, 6887, 6891, 6890

Top punched card per input:
Training results: 7803 correct recognitions of 27222
Test results: 812 correct recognitions of 3000

Top 2 (5%) punched cards per input:
Training results: 8493 correct recognitions of 27222
Test results: 895 correct recognitions of 3000

All punched cards:
Training results: 11955 correct recognitions of 27222
Test results: 1168 correct recognitions of 3000

Punched card bit length: 256

Average single-shot correct recognitions on fine-tune iteration: 7408, 7517, 7567, 7608, 7631, 7650, 7662, 7672, 7682, 7688, 7696, 7699, 7699, 7705, 7704

Top punched card per input:
Training results: 8384 correct recognitions of 27222
Test results: 876 correct recognitions of 3000

Top 1 (5%) punched cards per input:
Training results: 8384 correct recognitions of 27222
Test results: 876 correct recognitions of 3000

All punched cards:
Training results: 11949 correct recognitions of 27222
Test results: 1163 correct recognitions of 3000

Press "Enter" to exit the program...
```
