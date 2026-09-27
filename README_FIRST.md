# 20ME406P CFD and Heat Transfer Lab
## Google Colab Edition

This is the student-facing Colab release. No local Python, Jupyter, compiler, NumPy, Matplotlib, or solver installation is required.

## Student workflow

1. Open Google Colab.
2. Use File > Upload notebook.
3. Upload the assigned notebook from `colab_notebooks/`.
4. Save a copy in Google Drive.
5. Use `quick` only to check execution. Use `lab` or an approved `custom` case for the report.
6. Select Runtime > Run all.
7. Set `DOWNLOAD_RESULTS = True` in the final download cell and run it.

Each experiment notebook is self-contained. It writes the tested solver into the temporary Colab runtime, runs the solver, reads CSV summaries, plots results, previews a VTK scalar field inline, and creates a ZIP containing all generated files.

## Important limitations

- Colab storage is temporary. Download results before the runtime resets.
- A free Colab CPU runtime is sufficient. A GPU runtime is not required and does not accelerate these NumPy solvers.
- `quick` cases are deliberately small and are not valid report cases.
- Experiments 1, 3, 8, 10, and the natural-convection branch of Experiment 11 are reduced teaching models, not industrial CFD solvers.
- ParaView is optional. The notebooks provide inline field previews; VTK files remain available in the results ZIP.

## Package contents

- `colab_notebooks/00_Start_Here_Colab.ipynb`
- eleven self-contained experiment notebooks
- `manual/CFD_HT_Lab_Manual_Google_Colab_2026.pdf`
- `instructor_source/code/` for audit and maintenance
- `COLAB_VALIDATION_REPORT.md`
