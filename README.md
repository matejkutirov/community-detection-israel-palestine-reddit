# Unveiling Polarization: Community Detection and Sentiment Analysis on Reddit Discussions

### Authors
- Matej Kutirov - matej.kutirov@students.unibe.ch
- Flaminia Trinca - flaminia.trinca@students.unibe.ch
- Matilde De Luigi - matilde.deluigi@unifr.ch

## 1. Abstract

This study investigates the dynamics of community detection within a social graph constructed from over one million Reddit posts about the Israeli-Palestinian conflict. By employing sentiment analysis and various community detection algorithms, we analyzed the interplay between social support and emotional intensity in online discussions. Our customized Louvain algorithm demonstrated strong performance, validated through modularity and Normalized Mutual Information (NMI) metrics. Additionally, centrality measures provided insights into network structure and connectivity. Future work includes detailed sentiment analysis within major communities, temporal sentiment analysis, and the application of advanced machine learning models to enhance the accuracy and depth of insights. These efforts aim to deepen our understanding of community dynamics and sentiment expression in conflict-related social networks.

## 2. Installation instructions

### 2.1 Cloning the Repository

#### 2.1.1 Using Git
To clone this repository using Git, run the following command in your terminal:
```
git clone https://github.com/matejkutirov/community-detection-israel-palestine-reddit.git
```

#### 2.1.2 Using VS Code
```
1. Open Visual Studio Code.
2. Press Ctrl+Shift+P (or Cmd+Shift+P on Mac) to open the Command Palette.
3. Type Git: Clone and select it.
4. Paste the repository URL: https://github.com/matejkutirov/community-detection-israel-palestine-reddit.git
5. Choose a local directory to clone the repository into.
6. Once the repository is cloned, open the cloned folder in Visual Studio Code.
```

### 2.2 Local Machine
To install all the necessary libraries for the project on your local machine, run the following command:
```
pip install -r requirements.txt
```
The execution time of the whole notebook is around 30 minutes.

### 2.3 Google Colab

If you use Google Colab to run the notebook, click on this [link](https://colab.research.google.com/drive/1Uw_2uD76ic6BDpFBCGnYI94lVbT6PgGQ?usp=sharing)


1. First upload the `reddit.jpg` file to Colab. To do this:

- Click on `Files` in the left navigation bar.
- Click on `Upload to session` storage and select the `reddit.jpg` file from your local machine.

2. Second navigate to `Runtime -> Run All` in the menu.

The execution time of the whole notebook is around 50 minutes.
