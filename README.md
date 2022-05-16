### Dataset: [https://www.kaggle.com/olgabelitskaya/classification-of-handwritten-letters](https://www.kaggle.com/olgabelitskaya/classification-of-handwritten-letters)


# Data Description

### History
I made the database from my own photos of Russian lowercase letters written by hand.

### Content
The GitHub repository with examples - 
[GitHub](https://github.com/OlgaBelitskaya/deep_learning_projects/tree/master/DL_PP2)

### The main dataset (letters.zip)
- 1650 (50x33) color images (32x32x3) with 33 letters and the file with labels letters.txt.
- Photo files are in the .png format and the labels are integers and values.
- Additional letters.csv file.
- The file LetterColorImages.h5 consists of preprocessing images of this set: image tensors and targets (labels).
### The additional dataset (letters2.zip)
- 5940 (180x33) color images (32x32x3) with 33 letters and the file with labels letters2.txt.
- Photo files are in the .png format and the labels are integers and values.
- Additional letters2.csv file.
- The file LetterColorImages2.h5 consists of preprocessing images of this set: image tensors and targets (labels).
### The additional dataset (letters3.zip)
- 6600 (200x33) color images (32x32x3) with 33 letters and the file with labels letters2.txt.
- Photo files are in the .png format and the labels are integers and values.
- Additional letters3.csv file.
- The file LetterColorImages3.h5 consists of preprocessing images of this set: image tensors and targets (labels).

Letter Symbols => Letter Labels

а=>1, б=>2, в=>3, г=>4, д=>5, е=>6, ё=>7, ж=>8, з=>9, и=>10,
й=>11, к=>12, л=>13, м=>14, н=>15, о=>16, п=>17, р=>18, с=>19, т=>20,
у=>21, ф=>22, х=>23, ц=>24, ч=>25, ш=>26, щ=>27, ъ=>28, ы=>29, ь=>30,
э=>31, ю=>32, я=>33

Image Backgrounds => Background Labels

striped=>0, gridded=>1, no background=>2, graph paper=>3

### The new version (zip_letters.zip)

Letter Symbols => Letter Labels

а=>00, б=>01, в=>02, г=>03, д=>04, е=>05, ё=>06, ж=>07, з=>08, и=>09,
й=>10, к=>11, л=>12, м=>13, н=>14, о=>15, п=>16, р=>17, с=>18, т=>19,
у=>20, ф=>21, х=>22, ц=>23, ч=>24, ш=>25, щ=>26, ъ=>27, ы=>28, ь=>29,
э=>30, ю=>31, я=>32

'lowercase'=>00, 'uppercase'=>01

Image Backgrounds => Background Labels
'single-colored paper'=>00, 'striped paper'=>01, 'squared paper'=>02, 'graph paper'=>03

### Acknowledgements
As an owner of this database, I have published it for absolutely free using by any site visitor.

### Usage
Classification, image generation, etc. in the case of handwritten letters with a small number of images are useful exercises.

### Improvement
There are lots of ways for increasing this set and the machine learning algorithms applying to it.

- For example: add the same images but written by another person or add capital letters.
