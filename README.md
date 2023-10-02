# Multilanguage Data Generation

## 📗 Table of Contents

 1. [📖 About the Project](#-about-the-project)
 2. [Tech Stack](#tech-stack)
 3. [💻 Getting Started](#-getting-started)
     - [Installation](#installation)
     - [Usage](#usage)
       - [Generating Language-Specific JSONL Files](#generating-language-specific-jsonl-files)
       - [Consolidating Translations to JSON](#consolidating-translations-to-json)
 4. [👥 Authors](#-authors)
 5. [🤝 Contributing](#-contributing)
 6. [⭐️ Show your support](#-show-your-support)
 7. [🙏 Acknowledgements](#-acknowledgements)
 8. [📝 License](#-license)

📖 **About the Project**

The "Multilanguage Data Generation" project entails creating distinct JSONL files for English, Swahili, and German in test, train, and dev sets, and consolidating English-to-other-language translations in a formatted JSON file.

**Tech Stack**

- Python
- Visual Studio Code IDE

💻 **Getting Started**

To get a local copy up and running, follow these steps.

**Installation**

 1. Clone this repository to your desired folder using the following command:

      ```shell
      cd Group_CAT 
      git clone https://github.com/George-Stephen/Multilanguage-Data-Generation

 2. Set up your Python3 development environment using the following command:

     ```shell
     python -m venv env

 3. Activate your Python3 development environment using the following command:

     ```shell
     env\Scripts\activate

 3. Navigate to the data folder and place your input data files in the corresponding language directories (e.g., en, sw, de) inside the data folder.
 4. Open a terminal or command prompt and navigate to the project's root directory.
 5. Navigate to the main.py file and Comment out the generate_excel function call  
 6. Run the following command to generate the EXCEL files for each language:
     ```shell
     python main.py

**Consolidating Translations to JSON**
To consolidate translations from English to other languages into a formatted JSON file, follow these steps:

 1. After generating the language-specific JSONL files, ensure they are available in the output directories.
 2. Navigate to the main.py file and Comment out the process_json function call  
 3. Run the following command to consolidate translations:
     ```shell
     python main.py


👥 **Authors**

👤 Jackson Lowasa
      GitHub: @githubhandle

👤 George Steven
      GitHub: @George-Stephen
      
👤 Charity Claire
      GitHub: @githubhandle

👤 Shaleen Ndirangu
      GitHub: @githubhandle

👤 Mwangi Patience
      GitHub: @githubhandle


🤝 **Contributing**

Contributions, issues, and feature requests are welcome!

🙏 **Acknowledgements**

Acknowledgements.

📝 **License**
