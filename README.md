# Customer Segmentation Clustering

Dieses Projekt zielt darauf ab, Kunden eines Supermarkts basierend auf ihrem Kaufverhalten zu segmentieren. Ziel ist es, gezielte Marketingstrategien zu entwickeln, die den Umsatz durch personalisierte Kampagnen steigern.

## Methodik
- **Datenaufbereitung**: Bereinigung und Transformation der Kundendaten (z. B. Umgang mit Ausreißern, Erstellung neuer Features)
- **Dimensionsreduktion**: Anwendung von PCA, um hochdimensionale Daten auf die wichtigsten Merkmale zu reduzieren.
- **Clustering-Algorithmen**:
  - K-Means Clustering
  - Hierarchisches Agglomeratives Clustering (HAC)
- **Evaluation**: Silhouette-Score und Davies-Bouldin-Index zur Bewertung der Clusterqualität.
- **Interpretation**: Entwicklung von spezifischen Marketingempfehlungen basierend auf den Cluster-Ergebnissen.

## Libraries
- **Pandas**, **NumPy**: Datenmanipulation und -analyse.
- **Seaborn**, **Matplotlib**: Visualisierung.
- **Scikit-learn**: Clustering, PCA und Gütemaße.
- **Scipy**: Hierarchische Clusterbildung.
- **Yellowbrick**: Visualisierung von Silhouette-Plots.
