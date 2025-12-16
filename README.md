# Deploy ML models with FastAPI, Docker

> Learn from Demo Video — Build ML model with FastAPI: https://www.youtube.com/watch?v=wKdCmfXk4sM

#### Language Detector
Link for Dataset: https://www.kaggle.com/datasets/moazirfan/language-detection-dataset

This is a language detector model which can predict 17 different languages.
1) English
2) Malayalam
3) Hindi
4) Tamil
5) Kannada
6) French
7) Spanish
8) Portuguese
9) Italian
10) Russian
11) Sweedish
12) Dutch
13) Arabic
14) Turkish
15) German
16) Danish
17) Greek

---

### 1. Develop and save the model with this Colab

[Open Colab](https://colab.research.google.com/drive/1uaALcaatvxOu42IhQA4r0bahfdpw-Z7v?usp=sharing)

### 2. Create Docker container

```bash
docker build -t app-name .

docker run -p 80:80 app-name
```

