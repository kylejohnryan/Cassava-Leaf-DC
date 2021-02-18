# RC-Audio-Detection

As the second-largest provider of carbohydrates in Africa, cassava is a key food security crop grown by smallholder farmers because it can withstand harsh conditions. At least 80% of household farms in Sub-Saharan Africa grow this starchy root, but viral diseases are major sources of poor yields. With the help of data science, it may be possible to identify common diseases so they can be treated.

Existing methods of disease detection require farmers to solicit the help of government-funded agricultural experts to visually inspect and diagnose the plants. This suffers from being labor-intensive, low-supply and costly. As an added challenge, effective solutions for farmers must perform well under significant constraints, since African farmers may only have access to mobile-quality cameras with low-bandwidth.

![alt text](https://github.com/kylejohnryan/Casava-Leaf-DC/blob/main/example-classification.png?raw=true)

This notebook utilizes the ResNet-152 Model and is trained on a dataset of 21,367 labeled images collected during a regular survey in Uganda. Most images were crowdsourced from farmers taking photos of their gardens, and annotated by experts at the National Crops Resources Research Institute (NaCRRI) in collaboration with the AI lab at Makerere University, Kampala. This is in a format that most realistically represents what farmers would need to diagnose in real life.

The goal of this notebook is to classify each cassava image into four disease categories or a fifth category indicating a healthy leaf. Ideally--this notebook will help farmers be able to quickly identify diseased plants, potentially saving their crops before they inflict irreparable damage.
