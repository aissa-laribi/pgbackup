pgbackup
========

CLI for backing up remote PostgreSQL databases locally or to AWS S3.

#Usage

Pass in full database URL, the storage driver, and the destination.

S3 Example w/ bucket name:

'''

Local Example w/ local path:

$ pgbackup postgres://bob@example.com:5432/db_one --driver local /
var/local/db_one/backups
'''

## Installation From Source

To install the package after you've cloned the repository, you'll 
want to run the following command from within the project directory:

'''

$ pip install --user -e
'''

## Preparing for Development

Follow these steps to start developing with this project:

1. Ensure 'pip' an 'pipenv' are installed
2. Clone repository: 'git clone git@github.com:aissa-laribi/pgbackup'
3. 'cd' into repository
4. Activate virtualenv: 'pipenv shell'
5. Install dependencies: 'pipenv install'


