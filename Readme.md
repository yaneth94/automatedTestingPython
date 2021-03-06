# Python test

## Command to run Doctest
```
	python -m doctest name.ext
```

## Command to see more detail Doctest
```
	python -m doctest -v name.py
```
## To avoid the doctest command

This validation can be added in the file

```
	if __name__ == '__main__':
		import doctest
		doctest.testmod()
```

Then just run
```
	python name.py
```

Always to see more information

```
	python name.py -v
```

## Using assert

```
	assert True, "Mensaje extra"
```

## Pytest

To be able to use the library install

```
	pip install -U pytest
```

### Use pytest

```
	pytest name.py
```

### Install coverage
```
	pip install coverage
```

### Generate coverage
```
	coverage report name.py
```

### Generate and see information coverage
```
	coverage report -m name.py
```

### Generate testing coverage
```
	coverage run name.py
```

### Generate html coverage
```
	coverage report test_shopping_cart.py
```

### Server with Python
```
	python -m http.server
```
