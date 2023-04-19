## Installation

[Installlation link](https://labelstud.io/guide/install.html)

### Installation with pip

```bash
pip install label-studio
```
### Starting label studio
```bash
label-studio start
```
Label studio demo:
- Overview of label-studio (creating a new project)
- Loading data into Label studio
- Labelling Interface
- Annotations
- Exporting Annotations

## Label Studio ML backend

## What is the Label Studio ML backend?

Reference: https://github.com/heartexlabs/label-studio-ml-backend

The Label Studio ML backend is an SDK that lets you wrap your machine learning code and turn it into a web server. You can then connect that server to a Label Studio instance to perform 2 tasks:

-   Dynamically pre-annotate data based on model inference results
-   Retrain or fine-tune a model based on recently annotated data

Installation:
```bash
pip install label-studio-ml
```

ML-backend demo:
- Retrive predictions from the ML-model 
- Retrain/finetune the model 

![ml_backend](./images/ml_backend.excalidraw.svg)