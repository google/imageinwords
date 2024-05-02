The dataset is presented in `jsonl` format and consists of dense human-authored image descriptions using IIW's annotation framework and human SxS comparisons on 112 images covering [Densely Captioned Images (DCI)](https://github.com/facebookresearch/DCI) full test set.


| key       | interpretation | 
| :-------- | :------ |
| IIW   |   human-authored description from IIW's annotation framework  |
| ex_id   |   annotation identifier as defined in DCI's dataset  |
| image   |   image identifier as defined in DCI's dataset  |
| metrics/* | 5 point scale comparison between IIW and DCI's human-authored description as described in the IIW paper.|
