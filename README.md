## Protein Fitness Landscape Prediction using ESM-2 and Machine Learning

Created this repository for my course project in the subject **AI in Biology** under Dr. Prof. Kavitha Thirumurugan.
This repository provides a Jupyter Notebook to visualize **predicted mutation effects** on the insulin protein (PDB ID: 3I40) using 3D structural visualization with **3Dmol.js** and an embedded **horizontal colorbar**. The project allows users to map numerical scores (e.g., mutation effects, experimental metrics, or computational predictions) onto the protein structure for intuitive analysis.

---

## Features

- **3D Visualization**: Interactive 3Dmol.js view of insulin, with residues colored according to normalized scores.
- **Residue-specific Mapping**: Each residue is colored based on a per-residue score, allowing easy identification of regions of interest.
- **Embedded Colorbar**: Horizontal colorbar inside the figure with a clear label for predicted effects.
- **Easy Setup**: Runs with standard Python libraries: `numpy`, `matplotlib`, `py3Dmol`, `requests`.
- **Interactive Exploration**: Fully compatible with **Google Colab** for immediate online execution.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Diyasengupta2807/insulin_heatmap.git
cd insulin_heatmap
```
2. Install required packages

```bash
pip install numpy matplotlib py3Dmol requests
```
3. Open the notebook in Jupyter or Colab:

```bash
jupyter notebook Protein_Insulin_Heatmap.ipynb
```
## Usage
Replace the example heatmap scores with your own per-residue data.
Run the notebook cells to:
- Download the insulin PDB file.
- Normalize scores to a 0–1 range.
- Visualize the 3D protein structure with colored residues.
- Display the horizontal colorbar with appropriate labeling.
- Explore different colormaps by changing the cmap variable in the notebook.

## Example Output
- 3D interactive insulin structure with residues colored by score.
- Horizontal colorbar labeled "Predicted Mutation Effect".
- Title indicating *Protein: insulin*

## References
- RCSB Protein Data Bank (PDB): https://www.rcsb.org/
- 3Dmol.js Documentation: http://3dmol.csb.pitt.edu/doc/index.html
- Matplotlib Colormaps: https://matplotlib.org/stable/tutorials/colors/colormaps.html

