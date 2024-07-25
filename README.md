
# Semgrep Rules🛡️

This project includes a set of rules for the Semgrep tool to detect common vulnerabilities in programs written with Python and the Django framework. The goal of this project is to help developers quickly identify and fix security vulnerabilities in their code.

🔰Detection of common vulnerabilities: My rules are able to detect various vulnerabilities including

🔷Command Injection

🔷XXE

🔷Open Redirect

🔷XSS

🔷...

🔰Detection of security problems in the Setting.py file:
Special rules are written to identify security problems that exist in the project's Setting.py file so that these problems can be warned. Problems like:

🔷Enable debug mode

🔷Using a hard-coded encryption key

🔷Enable the secure feature for cookies

🔷...

🔰Focus on Django: This project focuses specifically on the Django framework and includes dedicated rules to identify security issues related to this framework.
Ease of use: Using Semgrep and the rules provided in this project, you can quickly scan your code and identify vulnerabilities.


## requirement❗
🔷Python 3

🔷Semgrep


## Usage/Examples✅

install Semgrep
```bash
pip3 install semgrep
```

```bash
git clone https://github.com/Mr-Hosseinzadeh/Semgrep-Ruls.git

```
```bash
cd {Project Folder}
```
```bash
semgrep --config {path}/Semgrep-Ruls .
```


## 🛠 Skills
🔷Python

🔷Django

🔷Vue.js


## Sources🔗

[Semgrep](https://semgrep.dev/docs/)



