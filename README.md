# AI-Image-Classifier

**Building AI Image Classifier from scratch**

## Description

**An AI  application that classify images.**

## Demonstration

![](assets/AI_Image_Classifier_1.gif)

![](assets/AI_Image_Classifier_2.gif)

## How to use this project ?


**Creating and activating a virtual environment**

````
python3 -m venv .venv
````

````
source .venv/Scripts/activate
````


**Installing  uv using pip**

```bash
pip install uv
```

**Starting uv environment with default files**

```bash
uv init . (initialising a uv project inside one directory)
```

**Installing necessary libraries with uv**

```bash
uv add streamlit tensorflow opencv-python
```


**Running the main file using streamlit**

```bash
uv run streamlit run main.py
```

## Tools :

- **streamlit**
- **opencv-python**
- **tensorflow**

**uv documentation :**

[https://docs.astral.sh/uv/getting-started/installation/#standalone-installer](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer)