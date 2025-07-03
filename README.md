# 🧴 Skincare Product Recommendation System (MedTourEasy Internship)

This project recommends skincare products for **dry skin** based on product ingredients and skin type suitability using dimensionality reduction and similarity analysis.

## 📁 Dataset
- Source: Provided by MedTourEasy
- File: `cosmetics.csv`
- Contains: Product name, brand, ingredients, price, ratings, and skin-type suitability flags

## 🛠️ Tools & Libraries Used
- Python
- pandas
- NumPy
- scikit-learn (t-SNE, Euclidean Distance)
- Bokeh (Interactive Visualization)

## 📌 Objective
To help users with **dry skin** discover alternative skincare products that have similar chemical components and performance, using a content-based recommendation approach.

## 📈 Methodology
1. **Filter** data for "Moisturizer" products suitable for dry skin.
2. **Extract features** (`Dry`, `Oily`, `Sensitive`, etc.).
3. **Dimensionality reduction** using t-SNE.
4. **Visualize** products using Bokeh interactive plot.
5. **Recommend** top 5 similar products using Euclidean distance.

## 📊 Output
- A scatterplot showing how different moisturizers relate based on t-SNE mapping.
- A simple recommendation system: input a product name, get 5 similar alternatives.

🔗 Author
Devanshu Mahala
MedTourEasy Data Science Intern
