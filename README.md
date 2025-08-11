# syncora-benchmarks

Syncora Benchmarks is a plug and play toolkit to evaluate synthetic data quality. Add CSVs from any generator and get instant fidelity metrics and visual comparisons with simple file naming.
---

## What’s Inside

- **`Syncora_vs_Gretel_vs_MostlyAI_metrics_comparison.ipynb`**  
  A Jupyter Notebook that:
  1. Loads your real & synthetic datasets  
  2. Computes a suite of similarity & fidelity metrics  
  3. Visualizes comparative results  

- **`README.md`**  
  This overview file.

- **Raw / Synthetic Data Files**  
  Place your CSVs here following the naming convention:  <generator_name>_synthetic.csv

---

## Template Usage

1. **Generate synthetic data**  
 Use any platform or in-house model to produce a CSV.

2. **Name your output**  
 Rename your file to: mygenerator_synthetic.csv

_e.g._ `Syncora_synthetic.csv`, `Gretel_synthetic.csv`, etc.

3. **Drop it into this repo**  
Place your CSV alongside the notebook in the same folder.

4. **Edit & run the notebook**  
- Open `Syncora_vs_Gretel_vs_MostlyAI_metrics_comparison.ipynb`.  
- The code automatically discovers all `*_synthetic.csv` files.  
- Execute all cells to regenerate metrics and plots.

---

## Adding New Generators or Datasets

1. Generate your synthetic CSV and name it `<your_name>_synthetic.csv`.  
2. (Optionally) Add a short description in the notebook’s metadata.  
3. Re-run the notebook — your new results will be appended to the comparison charts.

---

## Contributing

1. Fork this repository.  
2. Create a feature branch (`git checkout -b feature/xyz`).  
3. Submit a pull request with your updates.  
4. Ensure the notebook runs end-to-end without errors.

---

## License

This project is released under the [MIT License](LICENSE).
