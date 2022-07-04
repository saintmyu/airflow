# Airflow
Airflow installation on windows 10 with WSL

## Install WSL (https://insaid.medium.com/setting-up-wsl-2-in-windows-10-87e819d08d2e)
#### 1. Go to Microsoft Store, search Ubuntu, click GET

#### 2. Update and Upgrade Ubuntu version
> sudo apt-get update

## Install Airflow (https://insaid.medium.com/setting-up-apache-airflow-in-windows-using-wsl-8e0a87cd4945)
#### 1. Install pip on WSL
> sudo apt install python3-pip

#### 2. Install virtualenv package
> sudo pip3 install virtualenv

#### 3. Create a virtual environment
> virtualenv airflow_env

#### 4. Activate the environment
> source airflow_env/bin/activate
