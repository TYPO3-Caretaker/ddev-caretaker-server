# ddev Setup for Caretaker Server

## installation

* Install docker and ddev (https://ddev.readthedocs.io/en/latest/)
* clone repo and start ddev projekt:

```
git clone git@github.com:TYPO3-Caretaker/ddev-caretaker-server.git
cd ddev-caretaker-server
ddev start
ddev import-db --src=db.sql
open http://caretaker-server.ddev.local/typo3/
# use admin / password for BE Login
```
