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