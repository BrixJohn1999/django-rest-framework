## Install this dependencies

`python -m pip install django`
`python -m pip install djangorestframework`
`python -m pip install pygments`

## To Delete the database and create again

`rm db.sqlite3`
`rm -r snippets/migrations`
`python manage.py makemigrations snippets`
`python manage.py migrate `
` `
