# Data preparation stage

- Convert my data into train and test.tsv in 70:30 ratio

````
data.xml
    |-train.tsv
    |-test.tsv
````

- We are choosing only three tags in the XML data -1. row Id, 2.Title and Body, 3.Tags (Stackoverflow tags specific to Python)

|Tags|Features names|
|-|-|
|row Id|row ID|
|Title and Body|text|
|stackoverflow tags|Label - Python|
