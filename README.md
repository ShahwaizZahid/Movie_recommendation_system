# 🎬 Movie Recommendation System

## 📌 Project Overview

This project builds a collaborative filtering-based Movie Recommendation System using user ratings. The system predicts and recommends movies based on user similarities.

## 🚀 Features

- **User-Item Matrix:** Converts user ratings into a structured matrix.
- **Cosine Similarity:** Calculates similarity scores between users.
- **Weighted Rating Calculation:** Predicts ratings based on similar users' preferences.
- **Top-N Movie Recommendations:** Suggests the most relevant movies to a user.

## 🔧 Technologies Used

- **Python** (for data processing and model implementation)
- **Pandas** (for data manipulation)
- **Scikit-learn** (for MinMaxScaler and cosine similarity calculations)
- **NumPy** (for mathematical operations)

## 📂 Project Workflow

### 1️⃣ Data Preprocessing
- Load and clean the dataset.
- Normalize ratings using MinMaxScaler.

### 2️⃣ User-Item Matrix Creation
- Convert data into a user-item matrix using `pivot()`.

### 3️⃣ Compute User Similarity
- Calculate cosine similarity between users.
- Store results in a similarity matrix.

### 4️⃣ Movie Recommendation
- Identify top similar users.
- Compute weighted ratings based on user similarity.
- Recommend top-N movies the user hasn't watched.

## 📌 Example Output

**Recommended Movies for User 0:**

| Movie ID | Predicted Rating |
|----------|-----------------|
| 181      | 0.646814        |
| 174      | 0.538242        |
| 100      | 0.470174        |
| 127      | 0.462141        |
| 1        | 0.456209        |

## 🎯 Benefits

✅ Personalized movie recommendations 📽️  
✅ Efficient collaborative filtering approach 🔄  
✅ Scalable for large datasets 📊  

## 🔥 Future Improvements

- Implement content-based filtering to enhance recommendations.
- Use deep learning models (Neural Networks, Autoencoders).
- Optimize performance for real-time recommendations.

## 📌 Conclusion

This project provides an effective recommendation engine based on collaborative filtering. It demonstrates how machine learning techniques can be leveraged to predict user preferences and deliver personalized content.

