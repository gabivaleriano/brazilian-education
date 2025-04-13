# 🇧🇷 brazilian-education

This repository contains Jupyter notebooks and datasets related to an analysis of public discourse on education in Brazil. The analysis focuses on extracting and comparing topics from **official government news** and **video interviews** during the period **2019–2022**.

---

## 📒 Notebooks

### `topics_news.ipynb`

- Retrieves news articles from the official website of the Ministry of Education (MEC) between 2019 and 2022.
- Processes the textual content.
- Extracts and visualizes topics using natural language processing techniques.

### `topic_interviews.ipynb`

- Collects auto-generated subtitles from educational news videos published on YouTube.
- Processes the subtitle text.
- Extracts and analyzes topics using similar NLP techniques.

---

## 📂 Data Files (`.csv`)

### `df_interviews.csv`

- Contains raw subtitles automatically extracted from YouTube.
- Includes intermediate outputs from each preprocessing step.

### `df_news.csv`

- Contains 1,480 news articles collected from the Ministry of Education website (last accessed: 2023-06-03).
- Includes intermediate outputs from each preprocessing step.

---

## 📄 Original Paper

The analysis presented in this repository was developed as part of a **post-graduate course**.  
A summary of the study was accepted and presented at a **conference**.

The full paper is available in the file: `topics.pdf`.

---

## 📢 Citation

If you use this work in your research or academic projects, please cite:

@inproceedings{valeriano2024topics,
  author={Valeriano, Maria Gabriela and Abuabara, Leila and Belderrain, Carmen and Lorena, Ana Carolina},
  title={Extracting topics from Brazilian Education discourse: insights to support public policies},
  booktitle={LVI Simpósio Brasileiro de Pesquisa Operacional (SBPO 2024)},
  year={2024},
  address={Fortaleza, Brasil},
  organization={SOBRAPO}
}
