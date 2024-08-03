# Image Classification using UiPath AI Centre

## Steps to get started

### Cloud
- Activate Pro Subscription in [UiPath Cloud](https://cloud.uipath.com)
- Go to `admin` panel --> `services`
- Click on `AI Centre` and click `Launch`
- Create a new project in AI Centre
- Get the Fruits image dataset from [here](https://drive.google.com/file/d/1TLZajs8oiJ4ERp-eNrk6j282LRELTnD-/view?usp=classroom_web&authuser=0)
- Load the Dataset in AI centre --> `Datasets`
- Load the ML Package from `ML Packages` --> `Out of the box Packages` --> `UiPath Image Analysis` --> `ImageClassification`
- In `Pipelines` , create a new pipeline for Training and choose the `Train` dataset
- After successful completion of training, repeat for Evaluation using `Evaluation` dataset and choose subversion `1`
- Add this skill to `ML Skills`

### UiPath Studio
Packages required
```
UiPath.WebAPI.Activities
UiPath.MLServices.Activities
```
Use the Activity in this github.