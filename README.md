# DDEV Setup for TYPO3 extension caretaker

## Requirements

* Docker + DDEV (https://ddev.readthedocs.io/en/latest/)

## Installation

```
git clone https://github.com/TYPO3-Caretaker/ddev-caretaker-server.git && \
cd ddev-caretaker-server && \
git checkout TYPO3_8 && \
ddev start && \
open https://ddev-caretaker-server.ddev.site/typo3/
```

BE-User: admin
Password: password

## Configuration

If you use more DDEV projects (like https://github.com/TYPO3-Caretaker/ddev-caretaker-instance), 
use `ddev-<projectname>-web` as hostname in caretaker instance nodes for communication 
(see https://ddev.readthedocs.io/en/latest/users/faq/).
