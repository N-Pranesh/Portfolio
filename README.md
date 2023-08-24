<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.text {
  flex: 1;
  padding: 20px;
}

.image {
  flex: 1;
  max-width: 300px; /* Adjust the image width */
  text-align: right;
}

.image img {
  max-width: 100%;
  border-radius: 5px; /* Add a border radius for a nice effect */
}
</style>
</head>
<body>

<div class="container">
  <div class="text">
    <h1>Pranesh Kumar Narasimhan</h1>
    <p>Data Scientist</p>
    <p>I am a passionate Data Scientist with a strong background in analyzing and deriving insights from complex datasets. My expertise includes machine learning, data visualization, and deep learning.</p>
    <p>Connect with me on <a href="https://www.linkedin.com/in/pranesh-narasimhan">LinkedIn</a> to learn more about my work and projects.</p>
  </div>
  <div class="image">
    <img src="/images/pranesh-1.jpeg" alt="Profile Picture">
  </div>
</div>

<div class="container">
  <div class="text">
    <h2>Analysis of Netflix</h2>
    <p>Analysed the Netflix dataset to reveal viewership habits and preferences for movies and TV shows. Cleaned and formatted the data and created interactive visualizations. Tools and technologies used: Python, Pandas, NumPy, Tableau.</p>
  </div>
  <div class="image">
    <img src="/images/netflix-analysis.png" alt="Netflix Analysis">
  </div>
</div>

<div class="container">
  <div class="text">
    <h2>Steel Plate Inspection System</h2>
    <p>Implemented a deep learning-based model for real-time detection of faults in steel plates. Diverse ML/DL models leveraged, Random Forest excelled (80.78% accuracy). Tools and technologies used: Python, Scikit-learn, Machine learning models.</p>
  </div>
  <div class="image">
    <img src="/images/steel-plate-inspection.png" alt="Steel Plate Inspection">
  </div>
</div>

</body>
</html>
