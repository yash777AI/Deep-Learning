# Deep-Learning Project
🔹 Built a Graph from User-Movie Interactions

Transformed the dataset into a graph structure, treating movies as nodes and user ratings as edges to capture relationships between movies based on shared audience preferences.

🔹 Implemented a GNN Model for Rating Prediction

Developed a Graph Convolutional Network (GCN) to predict movie ratings, solving the cold start problem where new movies lack sufficient ratings.

🔹 Optimized for Speed & Efficiency

Reduced dataset size for faster computation.
Used adjacency matrices instead of loops for efficient graph construction.
Chose GCN over GAT for lower computational overhead.
Implemented early stopping to enhance training efficiency.

🔹 Real-World Impact
This approach mirrors Netflix, Amazon, and YouTube's recommendation systems, ensuring faster and smarter content recommendations by learning from user behavior patterns rather than relying solely on raw ratings.
