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
│── src/                   # Source code
│── tests/                 # Unit tests
│── docs/                  # Documentation
│── .gitignore             # Ignore unnecessary files
│── README.md              # Project documentation
│── setup.py               # Package configuration
│── requirements.txt       # Dependencies
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


