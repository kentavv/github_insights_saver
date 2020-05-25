# github insights saver
Save github repository stats to a sqlite3 database to allow longer than 14 days of insights data


## Installation
`python setup.py install`

## Usage
```
    $ github_insights_saver
```

To use, install and run the command `github_insights_saver` or `python -m github_insights_saver`. Insights data are stored to the sqlite3 database file `insights_saver.db`. Running again, in the same directory, will update the database.

OAuth is recommended (basic authentication is deprecated.) Create an OAuth token by visiting https://github.com/settings/tokens and generate a token with the scope: public_repo. Place the token string into a file named `token` as the first line.
