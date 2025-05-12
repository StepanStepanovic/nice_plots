# nice_plots
# Interactive Visualization Companion for DMS Data Analysis

This repository accompanies the manuscript:  
**_Insights into Modifiers Effects in Differential Mobility Spectrometry: A Data Science Approach for Metabolomics and Peptidomics_**,  
published in *Journal of Mass Spectrometry*  
📄 [DOI: 10.1002/jms.5039](https://doi.org/10.1002/jms.5039)

## Overview

This repository provides the Python code and Jupyter Notebook used to:

- Generate complex figures from the manuscript purely with Python.
- Explore high-dimensional DMS data using interactive 4D plots.
- Demonstrate how interactive chemical plots can reveal deeper insights that are not easily conveyed in static figures.

The interactive visualizations, while referenced in the manuscript, could not be included directly due to format limitations. This codebase allows readers to recreate them locally for further exploration.

## Requirements

To run the provided `.ipynb` notebook, you will need to create a dedicated Conda environment:

```bash
conda create -n rdkitdash python=3.9 -y
conda activate rdkitdash
pip install dash plotly rdkit-pypi scikit-learn pandas
These are the minimal requirements needed to run the visualizations and reproduce the key plots.

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name ```

2. **Create and activate the environment**  
   ```
   conda create -n rdkitdash python=3.9 -y
   conda activate rdkitdash
   ```

3. **Install the required packages**  
   ```
   pip install dash plotly rdkit-pypi scikit-learn pandas
   ```

4. **Launch the notebook**  
   ```
   jupyter notebook
   ```
   Open the provided `.ipynb` file and run the cells.

## Notes

- The figures and dashboards are built entirely in Python, demonstrating reproducibility and flexibility for similar metabolomics and peptidomics datasets.
- Some figures from the manuscript are visualized in an interactive 4D format here, providing depth that static plots cannot capture.

## Citation

If you use this repository in your work, please cite the original manuscript:

> Zivojinovic, O., et al. *Insights into Modifiers Effects in Differential Mobility Spectrometry: A Data Science Approach for Metabolomics and Peptidomics.*  
> Journal of Mass Spectrometry, 2024.  
> [https://doi.org/10.1002/jms.5039](https://doi.org/10.1002/jms.5039)

## License

This repository is released under the MIT License.

---

For questions, suggestions, or contributions, please open an issue or pull request.

