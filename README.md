# cookiecutter-tmp
Cookiecutter template for data science projects

# {{ cookiecutter.project\_name }}

🚀 **{{ cookiecutter.project\_name }}** is a Cookiecutter template for quickly setting up a new project with best practices.

## 📦 Features

- Automatically generates a structured project layout.
- Customizable settings via `cookiecutter.json`.
- Pre-configured for easy deployment and version control.

## 🛠️ Installation

Ensure you have [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) installed:

```sh
pip install cookiecutter
```

## 🚀 Usage

To create a new project using this template:

```sh
cookiecutter gh:fcolome14/{{ cookiecutter.project_slug }}
```

You will be prompted to enter:

- `project_name`
- `project_slug`
- `author`

## 📂 Project Structure

After generation, your project will have the following structure:

```
{{ cookiecutter.project_slug }}/
│── data/                  # Raw & processed data
│   ├── raw/               # Unmodified original data
│   ├── processed/         # Cleaned/engineered data
│   ├── interim/           # Intermediate data (e.g., feature selection)
│   ├── external/          # External datasets (e.g., APIs, external sources)
│
│── notebooks/             # Jupyter notebooks
│   ├── 01_exploratory_analysis.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training.ipynb
│   ├── 04_evaluation.ipynb
│
│── src/                   # Source code
│   ├── __init__.py
│   ├── data/              # Data processing scripts
│   │   ├── make_dataset.py
│   │   ├── preprocess.py
│   ├── features/          # Feature engineering
│   │   ├── build_features.py
│   ├── models/            # Model training and evaluation
│   │   ├── train_model.py
│   │   ├── predict.py
│   ├── visualization/     # Data visualization
│   │   ├── visualize.py
│
│── tests/                 # Unit tests
│   ├── test_data.py
│   ├── test_features.py
│   ├── test_models.py
│
│── config/                # Configuration files
│   ├── params.yaml        # Hyperparameters
│   ├── config.json        # Model settings
│
│── reports/               # Reports and results
│   ├── figures/           # Plots, graphs, and visualizations
│   ├── final_report.pdf
│
│── deployment/            # Deployment scripts
│   ├── docker/
│   │   ├── Dockerfile
│   │   ├── docker-compose.yaml
│   ├── api/               # API for serving models
│   │   ├── app.py         # FastAPI/Flask app
│   ├── inference.py       # Run model inference
│
│── requirements.txt       # Dependencies
│── pyproject.toml         # Package metadata
│── setup.py               # Package installer
│── README.md              # Project documentation
│── .gitignore             # Ignore unnecessary files
│── .env                   # Environment variables (e.g., API keys)
│── Makefile               # Automation commands

```

## 📝 Customization

Modify `cookiecutter.json` to change default values:

```json
{
    "project_name": "My Project",
    "project_slug": "my_project",
    "author": "Your Name"
}
```

## 🔄 Updating the Template

If you want to update the template, modify the files inside `cookiecutter-{{ cookiecutter.project_slug }}` and push changes to your repository.

## 🤝 Contributing

Feel free to open issues or submit PRs to improve this template!

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


