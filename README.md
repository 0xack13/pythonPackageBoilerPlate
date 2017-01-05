# python Package boilerplate/template
A basic boilerplate for creating python package 

Simply complete the config placeholders in the 'setup.py' file with your package information:

```python
setup(name='MODULENAME',
	version='',
	description='',
	url='',
	author='',
	author_email='',
	license='',
	packages=['MODULENAME'],
	zip_safe=False)
```

Once the package information is comelpte, run the following:

```bash
python setup.py sdist
```

