# pythonPackageBoilerPlate
A basic boilerplate for creating python package 

Simply complete the config placeholders in the 'setup.py' file with your package information:

```
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

```
python setup.py sdist
```

