# Signature Verification
This Repository contains code for verification of signature

Tensorflow is used and details of folder is as follows -
* SignVerify.ipynb file contains model(Link to Colab notebook)
* forged and real folders contain dataset for this project in form of real and forged images respectively
* training folder will save the trained images
  
Images are stored in the format : XXXZZZ_YYY
XXX denotes id of the person who has signed on the document(ex -001)
ZZZ denotes the id of the person to whom the sign belongs in actual(ex- 001)
YYY deontes the n'th no.of attempt


Now if XXX == ZZZ then image is genuine otherwise the signature is forged
