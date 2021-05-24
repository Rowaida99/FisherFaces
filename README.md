We intend to perform face recognition. Face recognition means that for a given
image you can tell the subject id. Our database of subject is very simple. It has 40
subjects.

1)Download the Dataset and Understand the Format (10 Points)
a. ORL dataset is available at the following link.

https://www.kaggle.com/kasikrit/att-database-of-faces/downloads/att-
database-of-faces.zip/1

b. The dataset has 10 images per 40 subjects. Every image is a grayscale
image of size 92x112.

2)Generate the Data Matrix and the Label vector (10 Points)
a. Convert every image into a vector of 10304 values corresponding to the
image size.
b. Stack the 400 vectors into a single Data Matrix D and generate the label
vector y.
The labels are integers from 1:40 corresponding to the subject id.