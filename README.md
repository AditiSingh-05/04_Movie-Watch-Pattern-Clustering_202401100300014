
# **_Movie Watch Pattern Clustering_**

## **_Overview_**
This project uses **K-Means Clustering** to group users based on their **movie-watching behavior**. 
By analyzing viewing time, genre preferences, and rating behavior, the program reveals patterns in how users interact with movie content.

---

## **_Features Analyzed_**
- **Watch Time**: Hour of the day the user watches movies (0–23).
- **Genre Preference**: Movie genres like Comedy, Drama, Action, etc.
- **Rating Behavior**: User ratings (0 to 5 scale).

---

## **_Workflow Summary_**

### **1. Data Loading**
Reads movie data from a CSV file containing:
- `watch_time_hour`
- `genre_preference`
- `avg_rating_given`

### **2. Data Preprocessing**
- **Label Encoding**: Converts genre text into numeric format.
- **Feature Scaling**: Normalizes all features using **StandardScaler** for equal weight in clustering.

### **3. Clustering with K-Means**
- Uses `KMeans` algorithm from `sklearn`.
- Clusters data into **5 distinct user groups** based on similarity.

### **4. Visualization**
- Displays a **pie chart** showing the distribution of users across clusters.
- Helps understand behavior patterns visually.

---

## **_Purpose_**
This clustering helps identify trends in user habits and can be used to **enhance recommendation systems** or **personalize content delivery**.