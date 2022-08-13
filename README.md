### 'Punched cards' for Oracle-MNIST

*Object recognition by sparse random binary data lookup. Based on [this article](https://petr-kovalev.medium.com/punched-cards-object-recognition-97523a98857b)*

Performing single-shot Oracle-MNIST ancient characters recognition by lookup over the most representative sparse input bit sets of the training data (out of 28⋅28⋅8 = 6272 bits per training sample)

Bit vector set similarity evaluation using the maximum spanning tree is described in [this article](https://petr-kovalev.medium.com/bit-vector-set-similarity-maximum-spanning-tree-2121b05c7b29)

The same algorithm applied to the QMNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-qmnist)

The same algorithm applied to the Fashion-MNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-fashion-mnist)

### Program output:
```
Punched card bit length: 8

Top punched card per input:
Training results: 4687 correct recognitions of 27222
Test results: 505 correct recognitions of 3000

Top 39 (5%) punched cards per input:
Training results: 7221 correct recognitions of 27222
Test results: 772 correct recognitions of 3000

All punched cards:
Training results: 10676 correct recognitions of 27222
Test results: 1078 correct recognitions of 3000

Punched card bit length: 16

Top punched card per input:
Training results: 5855 correct recognitions of 27222
Test results: 611 correct recognitions of 3000

Top 19 (5%) punched cards per input:
Training results: 8032 correct recognitions of 27222
Test results: 845 correct recognitions of 3000

All punched cards:
Training results: 10684 correct recognitions of 27222
Test results: 1059 correct recognitions of 3000

Punched card bit length: 32

Top punched card per input:
Training results: 6754 correct recognitions of 27222
Test results: 715 correct recognitions of 3000

Top 9 (5%) punched cards per input:
Training results: 8337 correct recognitions of 27222
Test results: 883 correct recognitions of 3000

All punched cards:
Training results: 10737 correct recognitions of 27222
Test results: 1052 correct recognitions of 3000

Punched card bit length: 64

Top punched card per input:
Training results: 6953 correct recognitions of 27222
Test results: 759 correct recognitions of 3000

Top 4 (5%) punched cards per input:
Training results: 7851 correct recognitions of 27222
Test results: 835 correct recognitions of 3000

All punched cards:
Training results: 10762 correct recognitions of 27222
Test results: 1046 correct recognitions of 3000

Punched card bit length: 128

Top punched card per input:
Training results: 7324 correct recognitions of 27222
Test results: 805 correct recognitions of 3000

Top 2 (5%) punched cards per input:
Training results: 7863 correct recognitions of 27222
Test results: 809 correct recognitions of 3000

All punched cards:
Training results: 10748 correct recognitions of 27222
Test results: 1039 correct recognitions of 3000

Punched card bit length: 256

Top punched card per input:
Training results: 7921 correct recognitions of 27222
Test results: 822 correct recognitions of 3000

Top 1 (5%) punched cards per input:
Training results: 7921 correct recognitions of 27222
Test results: 822 correct recognitions of 3000

All punched cards:
Training results: 10729 correct recognitions of 27222
Test results: 1028 correct recognitions of 3000

Press "Enter" to exit the program...
```
