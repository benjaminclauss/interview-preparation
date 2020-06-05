Please note that array questions and string questions are often interchangeable.

### Hash Tables
```
# Declare a dictionary.
some_dict = {'Name': 'Ben', 'Age': 23}
some_other_dict = dict()

# Accessing the dictionary with its key.
print(some_dict['Name'])

# Update existing entry.
some_dict['Name'] = 'Bob'

# Remove entry.
del some_dict['Name']
# Remove all entries.
some_dict.clear()
# Delete entire dictionary.
del some_dict
```

### Arraylist & Resizable Arrays

Lists are resizable by default in Python.

```
names = ['Ben', 'Bob', 'Bill']
some_list = list()

for name in names:
    print(name)
```

Amortized insertion runtime is O(1).

### StringBuilder

```
some_name = 'Ben'
some_name += ' Clauss'
```