# flask-template
Repository creates for fast running development process with configuration for Flask framework, which are the same from project to project.

## Documentation
...

## Development
### Local development
* Check you have Python 3.7 installed by typing on commandline `python --version`
* Install environment
```
pip install virtualenv
virtualenv venv
CALL venv/Scripts/activate (on Windows)
source venv/bin/activate (on Linux)
pip install -r requirements.txt
```

* Run server `python manage.py runserver`
* Point your web browser to http://localhost:5000/

## Testing

### Code style
* Run `pycodestyle --exclude=venv,flask_inject.py,container.py --max-line-length=120 .`

### Unit tests

* Run `pytest`

## Authors
* Aleksandr Seliutin - [selutin99](https://github.com/selutin99)

## Contributing
Please, follow [Contributing](CONTRIBUTING.md) page.

## Code of Conduct
Please, follow [Code of Conduct](CODE_OF_CONDUCT.md) page.

## License
This project is Apache License 2.0 - see the [LICENSE](LICENSE) file for details
