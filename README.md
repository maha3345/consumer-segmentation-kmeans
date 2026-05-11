# Consumer Behavioral Segmentation Using K-Means

**Objective:** To apply unsupervised machine learning to segment 
retail consumers into distinct behavioral profiles based on financial 
habits — proving the existence of the Impulse Buyer demographic.

## Consumer Segments Identified (k=5)

| Cluster | Profile | Avg Income | Avg Spend Score |
|---|---|---|---|
| 0 | Average (Mid Income, Mid Spend) | $55.3k | 49.5 |
| 1 | Target (High Income, High Spend) | $86.5k | 82.1 |
| 2 | **Impulse Risk (Low Income, High Spend)** | $25.7k | 79.4 |
| 3 | Careful (High Income, Low Spend) | $88.2k | 17.1 |
| 4 | Sensible (Low Income, Low Spend) | $26.3k | 20.9 |

## Research Insight

The Impulse Risk cluster (Cluster 2) spends disproportionately 
relative to income — behaviorally consistent with emotionally-driven, 
spontaneous purchasing. Isolating this segment is directly relevant 
to studying the cognitive overload hypothesis in AI recommendation 
systems (Rai, Shukla & Pandey, 2025).

## Methodology

Unsupervised Machine Learning, Elbow Method (WCSS) for optimal K 
selection, K-Means clustering, Matplotlib visual quadrant mapping

200 retail consumers segmented | random_state=42 for reproducibility

## Tools

Python, Pandas, Scikit-Learn, Matplotlib

## Dataset

Mall Customers Dataset (included: `Mall_Customers.csv`)
