🧑‍💻 athul_nair — Personal Portfolio Python Package

A Python package that exposes my complete developer portfolio in a structured, programmatic, and beautifully formatted way.
It includes details about my skills, projects, experience, contact information, and more — all accessible via Python functions or a command-line interface (CLI).

Perfect for showcasing your developer identity in code form, demos, documentation, or automations.

🚀 Install
pip install athul-nair

🧠 Usage (Python API)
import athul_nair as athul

print(athul.profile_pretty())
print(athul.skills_pretty())
print(athul.about_pretty())
print(athul.contact_pretty())
print(athul.experience_pretty())
print(athul.projects_pretty())

🖥 Command Line Interface (CLI)

Once installed, you can run:

athul profile
athul skills
athul contact
athul experience
athul projects
athul about
athul name
athul title

Example:
athul skills


Outputs formatted skill categories beautifully.

📦 Available Sections
👤 Personal Info

Name

Title

About Me

Contact details

🧠 Skills

AI/ML & MLOps

Automation

Languages

Frontend & App Development

Backend & Cloud

Tools

💼 Experience

Each experience includes:

Role

Company

Description

🚀 Projects

Grouped by category:

AI / ML

Flutter Apps

📁 Project Structure
athul_nair/
│── __init__.py       # Main API and pretty-printers
│── cli.py            # Command-line interface logic
│── data.py           # Portfolio data (skills, projects, experience)
│
pyproject.toml        # Package configuration
README.md             # Documentation
LICENSE               # MIT License

🛠 Features

✔ Clean Python API
✔ Pretty formatted output
✔ CLI support
✔ Structured portfolio data
✔ Easy to extend or customize
✔ Represents your developer identity programmatically

📜 Example Output
Running:
athul profile


Produces:

NAME
-------------------------
Athul Nair

TITLE
-------------------------
AI/ML Developer · Flutter Developer · Automation Engineer

ABOUT
-------------------------
- I am an AI/ML and Flutter developer focused on intelligent systems...
- My background includes marketing, creative design...
- I enjoy creating Gen-Z styled applications...

🌐 Links

PyPI:
https://pypi.org/project/athul-nair/

GitHub:
https://github.com/Athul-n-air/pip_install_athul-nair

📜 License
MIT License
Copyright (c) 2025

❤️ Contributions

This is a personal portfolio library — but feel free to open issues or suggestions!
