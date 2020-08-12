# Screenshot comparison with Selenium

Simple automata to grab screenshots from two url addresses and then using
Pillow library create output file with marked regions that are different.


# Usage

* Install Python [https://www.python.org/downloads/](url) REMEMBER: add Python to system path!
* Clone this repository
* Enter project directory
* Create virtual environment: `pip -m venv venv`
* Activate virtual environment:

| Platform | Shell | Command to activate virtual environment |
| ------ | ------  | ------ |
| POSIX | bash/zsh | $ source <venv>/bin/activate |
|   | fish | $ . <venv>/bin/activate.fish |
|   | csh/tcsh | $ source <venv>/bin/activate.csh |
|   | PowerShell Core | $ <venv>/bin/Activate.ps1 |
| Windows | cmd.exe | C:\> <venv>\Scripts\activate.bat |
|   | PowerShell | PS C:\> <venv>\Scripts\Activate.ps1 |

* Run command to install required libraries: `pip install -r requirements.txt`
* In `screenshot.py` file edit `STAGING_URL` [L:9](https://gitlab.emakina.net/security/screenshot-selenium-comparison/blob/master/screenshot.py#L9) and `PRODUCTION_URL` [L:10](https://gitlab.emakina.net/security/screenshot-selenium-comparison/blob/master/screenshot.py#L10) links to proper environments to check
* Run Python script: `python screenshot.py`
* The output `results.png` file should have marked regions with differences

# Enjoy
