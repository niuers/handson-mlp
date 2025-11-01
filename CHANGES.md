# HOML PyTorch #1 versus HOML Keras & TensorFlow #3

I wrote three TensorFlow (TF) editions of this book, published by O'Reilly in 2017, 2019, and 2022. If you have already read the latest TensorFlow edition of this book, here are the main changes you will find in this book (for changes between editions 1 and 2, see https://homl.info/changes2, and for changes between editions 2 and 3, see https://homl.info/changes3):

* All the code in the book was updated to recent library versions.
* All the code in Part 2 was migrated from TensorFlow and Keras to PyTorch. There were significant changes in all of these chapters.
* TensorFlow-specific content was removed, including former Chapter 12 (Custom Models and Training with TensorFlow) and Chapter 13 (Loading and Preprocessing Data with TensorFlow), and former Appendices C (Special Data Structures) and D (TensorFlow Graphs).
* The new Chapter 10 now introduces PyTorch.
* I also added three new chapters on transformers (this is by far what required the most work, along with the SSM appendix):
    * Chapter 15 covers transformers for natural language processing, including how to build a chatbot.
    * Chapter 16 presents vision transformers and multimodal transformers.
    * Chapter 17, available online at https://homl.info/, discusses several advanced techniques to speed up and scale up transformers. This includes FlashAttention, mixture of experts (MoE), low-rank adaptation (LoRA), and many more.
* There are also three new appendices:
    * Appendix B (Mixed Precision and Quantization) explains how to shrink models so they can run faster and fit on smaller devices.
    * Appendix D (Relative Positional Encoding) discusses advanced positional encoding techniques for transformers.
    * Appendix E presents state-space models (SSMs).
* To make room for the newer content, the chapter on support vector machines (SVMs) was [moved online](https://homl.info) and renamed to Appendix C; the last two appendices are also online at the same URL, and the deployment chapter was partially merged into Chapter 10.

The three editions of the TensorFlow/Keras version of this book are nicknamed homl1, homl2, and homl3. This book, which is the first edition of the PyTorch version, is nicknamed homlp. Try saying that three times in a row.

Note that most of the changes compared to the latest TensorFlow edition are in the second part of the book. If you have read homl3, then don't expect big changes in the first part of the book, other than up-to-date libraries: the fundamental concepts of machine learning haven't changed since 2022.
