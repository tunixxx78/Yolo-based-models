# Community YOLO26 Models

This repository distributes community-trained object detection models based on Ultralytics YOLO26.

These are independently trained models, not official Ultralytics releases.

## License

The model weights in this repository are distributed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See [LICENSE](LICENSE) for the complete license text.

Use, modification, and redistribution, including commercial use, are permitted subject to the applicable AGPL-3.0 terms.

The models are not distributed under Apache-2.0 or MIT. Their availability does not grant permission to disregard AGPL-3.0 source availability, redistribution, notice, or applicable network interaction requirements.

Third-party software and datasets retain their respective licenses and copyright notices.

## Available Models

| Model file | Base checkpoint | Classes | Description |
|---|---|---|---|
| [Filename] | [Exact base checkpoint] | [Class list or link] | [Description] |

## Training Source Code

The dataset collection, annotation, training, and export tools are maintained separately:

https://github.com/tunixxx78/yolo-scraper-and-training

The inspected source revision is:

https://github.com/tunixxx78/yolo-scraper-and-training/tree/89f2e73593c688df45aaebeda4ce4eb680f4f05f

Tools in that revision:

- [Image collection — app.py](https://github.com/tunixxx78/yolo-scraper-and-training/blob/89f2e73593c688df45aaebeda4ce4eb680f4f05f/app.py)
- [Annotation and dataset export — annotate.py](https://github.com/tunixxx78/yolo-scraper-and-training/blob/89f2e73593c688df45aaebeda4ce4eb680f4f05f/annotate.py)
- [Training and ONNX export — train_yolo_models.py](https://github.com/tunixxx78/yolo-scraper-and-training/blob/89f2e73593c688df45aaebeda4ce4eb680f4f05f/train_yolo_models.py)
- [Workflow documentation](https://github.com/tunixxx78/yolo-scraper-and-training/blob/89f2e73593c688df45aaebeda4ce4eb680f4f05f/README.md)

The source revision used for each released model is identified below. The current default branch of the training repository may differ from the version used for training.

## Model Release and Training Details

- **Model filename and release:** [Filename and release tag]
- **Training source revision:** [Commit link corresponding to this model]
- **Starting checkpoint:** [Exact checkpoint name and its source]
- **Ultralytics version:** [Exact version used]
- **Python and training dependency versions:** [Versions or link to an environment file]
- **Training command:** [Exact command used]
- **Training configuration:** [Link to the run's args.yaml or equivalent settings]
- **Dataset configuration and class IDs:** [Link to dataset.yaml and class definitions]
- **Dataset version and split information:** [Version and train/validation/test details]
- **Custom modifications:** [Describe modifications or state that none were made]

The training source, custom modifications, and model-specific configuration needed for the applicable corresponding-source obligations are provided through the links above.

Corresponding source must remain available without an additional charge for as long as the associated model weights are distributed. A link to a newer or unrelated source revision is not a substitute for the source corresponding to a released model.

## Training Data

- **Dataset name and version:** [Name and version]
- **Original image sources:** [Sources and links]
- **Image licenses and required attribution:** [Details]
- **Annotation license and availability:** [Details and link]
- **Dataset download or access information:** [Link or accurate explanation of availability]
- **Redistribution limitations, if any:** [Details]

The model's AGPL-3.0 license does not relicense the training images or other third-party data.

Dataset access and redistribution are governed by the rights and licenses applicable to those materials. This repository does not grant rights to third-party images beyond those granted by their respective rightsholders.

## Upstream Project and Attribution

The models were trained using Ultralytics YOLO26.

- Ultralytics source: https://github.com/ultralytics/ultralytics
- Ultralytics licensing information: https://www.ultralytics.com/license
- Training workflow: https://github.com/tunixxx78/yolo-scraper-and-training

Ultralytics YOLO is developed by Ultralytics and its contributors. Applicable upstream license and copyright notices must be retained.

Community model training and publication: tunixxx78.

## Warranty and Evaluation

The models are provided without warranty to the extent permitted by applicable law, as specified in the AGPL-3.0 license.

Predictions may include false positives, missed objects, and incorrect classifications. Evaluate each model on representative independent data before using it in an application.
