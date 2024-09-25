## AirBnB_clone_v2

This repository hosts the code used to create a clone of the Airbnb website. The project uses Python and is divided into modules, i.e. different files that contain the code for different features and functionalities of the website.
The website features a database for storing user, place, state, city, amenity and review data.
The basic architecture of the project is as follows:

- setup_web_static.sh: This script sets up the web server and its static files.
- 1-pack_web_static.py: This script archives the static files for deployment.
- 100-clean_web_static.py: This script deletes outdated archive files.
- 101-setup_web_static.pp: This Puppet script sets up the web server and its static files.
- 2-do_deploy_web_static.py: This script deploys the static files to the host servers.
- 3-deploy_web_static.py: This script archives and deploys the static files to the host servers.
- console.py: This file contains the code for the interactive console, which allows users to create, show, update, destroy, and count objects of the different classes.
- run.bash: This script is used to run the application or command specified as the first argument, with the environment and storage type specified as the second and third arguments, respectively.
- setup_mysql_dev.sql: This SQL script creates the database and user for the development environment.
- setup_mysql_test.sql: This SQL script creates the database and user for the testing environment.
- test.bash: This script runs the unit tests for the project in both interactive and non-interactive modes, and also runs Python code style checks.

## Requirements

To run this project, you will need the following:

- Python 3.6 or later
- MySQL 5.7 or later
- pipenv

## Installation

To install the dependencies and set up the project, run the following commands:

```bash
git clone https://github.com/holbertonschool/AirBnB_clone_v2.git
cd AirBnB_clone_v2
pipenv install
pipenv shell
```

## Usage

To run the project, run the following command:

```bash
./run.bash
```

This will start the web server and open the interactive console.

## Contributing

Contributions to this project are welcome! Please read the [contributing guidelines](https://github.com/holbertonschool/AirBnB_clone_v2/blob/master/.github/CONTRIBUTING.md) before submitting a pull request.