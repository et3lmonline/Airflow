# Installing Apache Airflow

Airflow could be installed by [different ways](https://airflow.apache.org/docs/apache-airflow/stable/installation/index.html), here we will use the PyPI and Docker.

## Install on Windows 10 / WSL Using PyPI

### Install and configure WSL
- WSL stands for Windows Subsystem for Linux
- To activate WSL
  1. open start menu
  2. search for "Turn windows features on or off", make sure to activate these features, a Windows reboot may be required.
     1. Virtual Machine Platform
     2. Windows Subsystem for Linux
- Open Microsoft Store, search for "Ubuntu", select a version, then click "Get".
- After the application is downloaded, press "Open"
- Enter a username, and password
- Install and update the necessary Ubuntu packages
  ```bash
  sudo apt update && sudo apt -y upgrade
  ```



### Install Apache Airflow

## Install Airflow Using Docker-Compose

