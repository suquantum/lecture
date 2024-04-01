# Introduction
This material is an introduction to machine learning 101 with hands-on exercise materials. The following is the syllabus of this material.

### Contents of this Material
Introduction to the following subjects.
1. Setup procedure on macOS 12.2.1.
2. Explanation of Data Scientist tasks.
4. Numeriacal simulation.
5. Machine learning basic theory and programming.
    1. Supervised learning.
    2. Data understanding and visualization.

### Pre-requisites
1. Calculus: Basic algebra, probability theory such as the concept of expected value.
2. Programming: The codes are provided. Having a basic knowledge of Bash, Python is a plus.


---
## Setup and Installation
For using and developing tools and applications, you have to do the following things.
1. Set proper environment for tools.
2. Install tools and libraries that you are going to use.
3. Finally, start writing programs and scripts for your tasks.
The following are the process for the set up.

### Obtain local admin rights to have a privilege to set up the environment
If you belong to organization, please comply your policies to obtain local administration authentication.

### Setup Environment
* For macOS
    * Install Homebrew
        1. Turn off zscaler for allowing your machine to download necessary packages and libraries.
        2. Click magnifying glass symbol for Spotlight Searching.
        3. Type 'terminal' and click the icon.
        4. Execute the following command on the terminal
            ```
            /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
            ```
        5. Check there is no error message. If there is copy the log and ask to the manager for troubleshooting.
            * For more information
                * https://jptyoapl15.jp.kworld.kpmg.com/display/KTC/TAX+X+-+Annotator+Onboarding#TAXXAnnotatorOnboarding-SetupEnvironment
    * Install Virtual Environment for Tool
        1. Install miniconda with the executing the following command in the terminal.
            ```
            brew install Caskroom/cask/miniconda
            ```
        2. Download the Repository with the following command.
            ```
            git clone https://kpmgjp-prod-001@dev.azure.com/kpmgjp-prod-001/kpmgjp-intelligent-containers/_git/kit-fusion-area51
            ```
        3. Change the directory to the repository that you download with
            ```
            cd ml_101
            ```
            then, execute the following command.
            ```
            conda env create -f ml_101.yml
            ```
    * Run the application which is Jupyter Lab for hands-on programming application.
        1. Open a terminal.
        2. Go to the directory that you downloaded: By defualt, it will be under your home directory which you can change the directory with the following command
            ```
            cd ml_101
            ```
        3. Execute the following command to activate the environment
            ```
            conda activate ml_101
            ```
        4. Execute the following command to start the application
            ```
            jupyter lab ml_101_handson.ipynb
            ```
            and the application will pop up on your defualt browser.

---
### Questions, Feedback, and Troubleshooting
Contact the author for questions, feedback, and troubleshooting.

| Version | Date | Author |
| :-: | :-: | :-: |
|  0.0.1  | 2021/10/27 | Schun Uechi |