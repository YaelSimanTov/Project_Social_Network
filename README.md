# Facebook Pages Network Analysis

This project analyzes the network of Facebook pages using graph theory tools. It focuses on different page categories (such as politicians, government, TV shows, and companies) and visualizes both the entire network and relevant subgraphs.

## 📁 Dataset

The project uses the [Facebook Page-Page Network dataset](https://www.kaggle.com/datasets/rozemberczki/musae-facebook-pagepage-network) from Stanford's SNAP repository, which includes:

- `musae_facebook_edges.csv`: Undirected edges between Facebook pages.
- `musae_facebook_target.csv`: Category (label) assigned to each Facebook page.
- `musae_facebook_features.csv`: Page features (not used in this analysis).

## 📊 Project Goals

- Build a graph representation of Facebook pages.
- Create subgraphs for each page category (politician, government, tvshow, company).
- Visualize each category individually.
- Create a unified network visualization, with color-coded nodes.
- Visualize specific combinations (e.g., only politicians and government pages).

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NetworkX
- Matplotlib

## 🚀 How to Run

1. Clone the repository or download the code files.
2. Make sure you have the required packages:
   ```bash
   pip install pandas networkx matplotlib
