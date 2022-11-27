# CaseStudy_ForensicScienceService

## Summary

This Case Study involves a dataset from USA Forensic Science Service which has description of 6 types of glass; defined in terms of their oxide content (i.e. Na, Fe, K, etc). The task is to use K-Nearest Neighbor (KNN) classifier to classify the glasses.

The original dataset is available at (https://archive.ics.uci.edu/ml/datasets/glass+identification). For detailed description on the attributes of the dataset please refer to the original link of the dataset in the UCI ML repository.

In this task we perform exploratory data analysis on the dataset using Python Pandas, including dropping irrelevant fields for predicted values, and standardization of each attribute.

Following data cleaning, two Scikit-Learn KNN models should be created for two different distance metrics: Square Euclidean and Manhattan distance. The performance of the two models using different distance metrics is compared in terms of accuracy to the test data and Scikit-Learn Classification Report.

## About the Dataset

### Data Set Information:

Researcher conducted a comparison test of his/her rule-based system, BEAGLE, the nearest-neighbor algorithm, and discriminant analysis. BEAGLE is a product available through VRS Consulting, Inc.; 4676 Admiralty Way, Suite 206; Marina Del Ray, CA 90292 (213) 827-7890 and FAX: -3189. In determining whether the glass was a type of "float" glass or not, the following results were obtained (# incorrect answers):

Type of Sample -- Beagle -- NN -- DA
Windows that were float processed (87) -- 10 -- 12 -- 21
Windows that were not: (76) -- 19 -- 16 -- 22

The study of classification of types of glass was motivated by criminological investigation. At the scene of the crime, the glass left can be used as evidence...if it is correctly identified!

### Attribute Information:

1. Id number: 1 to 214
2. RI: refractive index
3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)
4. Mg: Magnesium
5. Al: Aluminum
6. Si: Silicon
7. K: Potassium
8. Ca: Calcium
9. Ba: Barium
10. Fe: Iron
11. Type of glass: (class attribute)

-- 1 building_windows_float_processed

-- 2 building_windows_non_float_processed

-- 3 vehicle_windows_float_processed

-- 4 vehicle_windows_non_float_processed (none in this database)

-- 5 containers

-- 6 tableware

-- 7 headlamps


