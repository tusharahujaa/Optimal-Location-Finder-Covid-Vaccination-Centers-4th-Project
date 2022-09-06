# Optimal Location Finder For Covid Vaccination Centers(4th Project)

This project identifies the optimal location of the vaccination centers in state of Tamil Nadu, India.

The optimal number and location of vaccination centers were predicted using the K-Means Clustering Technique, which was implemented on the COVID-19 dataset (source: Tamil Nadu Government official repository collected during the 2nd wave, May, 2021).

Here the model was implemented on Google-Colaboratory and the optimal number of clusters was predicted and analysed using the Elbow Method and the Silhouette Analysis Method.

The optimal predicted locations of the clusters (vaccination centers) were plotted on the map and visualised using the Folium framework and Opencage Geocoding API.

### Requirements
#### Install Required Libraries
```bash
   pip install opencage
```
```bash
   pip install sklearn
```
```bash
   pip install folium
```
```bash
   pip install pandas
```
```bash
   pip install matplotlib
```
**NOTE :-**
**Since maps cannot be displayed as an output in the python notebook, sample images are uploaded in the Images directory for reference.** 
