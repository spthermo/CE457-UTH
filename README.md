# CE457-UTH

## Εργασία

Στόχος της φετινής εργασίας είναι να δημιουργήσουμε ένα πρόγραμμα που λαμβάνει N εικόνες με μερική επικάλυψη και επιστρέφει τις εικόνες συρραμμένες.

### Αλγοριθμικά Βήματα

Το πρόγραμμα θα πρέπει να υλοποιηθεί σε γλώσσα PYTHON και να ακολουθεί τα παρακάτω βήματα:

1. Εύρεση κοινών χαρακτηριστικών μεταξύ εικόνων με αλγόριθμο SIFT
2. Εύρεση των outliers με τον αλγόριθμο RANSAC
3. Εφαρμογή μετασχηματισμού homography
4. Warping και blending εικόνων
5. Αποθήκευση πανοραμικής εικόνας

### Βιβλιοθήκες

* [matplotlib](https://matplotlib.org/)
* [python-opencv](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
* [numpy](https://numpy.org/)

### Παράδειγμα - Stitching 2 εικόνων

1. Αρχικές εικόνες 1 (left) και 2 (right)

<img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/1.jpg" width="250"> <img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/2.jpg" width="250">

2. SIFT features

<img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/keypoints.png" width="450">

3. SIFT signatures

<img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/sift_signatures.png" width="450">

4. Inliers (after removing outliers with RANSAC)

<img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/inliers.png" width="450">

5. Stitched image

<img src="https://github.com/spthermo/CE457-UTH/blob/main/examples/stitched.jpg" width="450">
