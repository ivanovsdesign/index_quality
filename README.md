# Index Quality Analysis 📊🔍

[![GitHub stars](https://img.shields.io/github/stars/ivanovsdesign/index_quality.svg)](https://github.com/ivanovsdesign/index_quality/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ivanovsdesign/index_quality.svg)](https://github.com/ivanovsdesign/index_quality/network)
[![GitHub issues](https://img.shields.io/github/issues/ivanovsdesign/index_quality.svg)](https://github.com/ivanovsdesign/index_quality/issues)

Welcome to the Index Quality Analysis repository! This project explores the performance of FAISS and Annoy indexing algorithms with various metrics to compare search quality.

## 🚀 Features

- **Index Comparison**: Compares the performance of FAISS and Annoy indexes using different distance metrics.
- **Quality Metrics**: Evaluates search quality using MAP@20, DCG@20, MRR, and ERR metrics.
- **Data-Driven Insights**: Provides a detailed analysis of the results to help choose the best indexing strategy for different scenarios.

## 📈 Results

The following table summarizes the search quality results for each index:

| Index Type       | MAP@20       | DCG@20       | MRR          | ERR          |
|------------------|--------------|--------------|--------------|--------------|
| faiss_L2         | 0.519605     | 3.139235     | 0.461988     | 0.144568     |
| faiss_IP         | 0.745815     | 3.419188     | 0.708333     | 0.336610     |
| annoy_angular    | 0.533772     | 3.057684     | 0.461988     | 0.156234     |
| annoy_euclidean  | 0.526550     | 3.147764     | 0.461988     | 0.145956     |
| annoy_manhattan  | 0.243591     | 1.513743     | 0.195767     | 0.101152     |

## 🛠️ Getting Started

To get started with the Index Quality Analysis project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ivanovsdesign/index_quality.git

2. **Navigate to the Project Directory:**

    ```bash
    cd index_quality
    ```
3. **Explore the Analysis:**

    - Review the code and documentation to understand how the indexes were created and evaluated.

    - Analyze the results to gain insights into the performance of each indexing method.

## 🤝 Contributing
Contributions are welcome! Please read the CONTRIBUTING.md for details on how to contribute to this project.

## 📄 License
This project is licensed under the MIT License.

## 📬 Contact
For questions or feedback, please open an issue on GitHub.

🌟 Thank you for visiting the repository! If you find this project helpful, please consider starring it to show your support. Happy coding! 🚀
