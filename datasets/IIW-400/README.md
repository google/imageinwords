## IIW-400

The dataset is presented in `jsonl` format and consists of 400 images sampled from [DOCCI' AAR](https://github.com/google/docci) dataset.


### Identifier
| key       | interpretation | 
| :-------- | :------ |
| image/key   |   image identifier as defined in DOCCI's dataset  |


### Detailed Image Descriptions

| key       | interpretation | 
| :-------- | :------ |
| IIW   |   human-authored description from IIW's annotation framework  |
| IIW-P5B   |   machine generated description from a PaLI 5B finetuned model on IIW training set  |


### Image Object Level Annotations

List of `json` object inside the `objects` key in the `jsonl` record. Each `json` object corresponds to one object in the image.

| key       | interpretation | 
| :-------- | :------ |
| label | human-authored free form object identifier |
| description | human-authored detailed object level description, taking the context of the image into account |
| normalized_coords | normalized coordinates of the human-annotated bounding box in `(_ymin, x_min, y_max, x_max)` format |



### Human SxS

| key       | interpretation | 
| :-------- | :------ |
| iiw-human-sxs-gpt4v | 5 point scale comparison between IIW human-authored and GPT-4V generated description as described in the IIW paper. The metrics are further noted as `metrics/*`.|
| iiw-human-sxs-iiw-p5b | 5 point scale comparison between IIW human-authored and IIW fine-tuned PaLI 5B generated description as described in the IIW paper. The metrics are further noted as `metrics/*`.|

