# Python-methods

## List methods
- l.append(ele)
- l.insert(index,ele)
- l.pop() -> removes from the last of list
- l.remove(element_to_be_removed) -> only removes the first occurance from the beginning of the list
- l[start:end] -> end is exclusive
- l[start: end :step] -> step to specify number of steps to take in between elements
- l.index(ele) -> gives the index of first occurance and throws error if the element is not present
- ele in l -> to check if ele is present in l
- ele not in l -> to check if ele is not present in l
- l.sort() -> inplace sorting of the list
- list compression -> [expression for loop if condition]

## Tuple Methods
- same as list, except they are immutable -> so methods which are mutating the Tuple are not applicable

## Dictinary methods
- d = {key: value, key: value} -> in this format key can be anything which is not mutable
- d = dict(key=value, key=value) -> dict constructor -> here we can only give cosntant values as key e.g title. "title", "1",1, (2,3) --> these are not accepted
- d.get(key) -> if key is not present, we will not get any error -> it will just return None
- d[key] -> gives error if key is not present
- d[key] = value -> updating the key's value or adding new entry
- del d[key] -> deletes the entry from the dictionary, if not present throws error
- d.pop(key) -> deletes the entry and returns just the value of the key 
- d.popitem() -> from 3.7 python version->deletes last entry and returns a tuple of key and value
- len(d) -> returns len of the dictionary
- key in d -> checks if the key is present in dictionary
- d1.update(d2) -> d1 will have all the items
- d.items() -> will return a list of tuple of key, value

## Set methods
- s = {key, key, key} -> keys should be immutable. Lists and dictionaries cannot be stored in set
- s = set(key,key,key)
- s.add(key) - to add a key to set
- s.update(new_set) -> s contains all the elements of s set and new_set set
- s.discard(key) or s.remove(key) -> To remove the key from the set
- Union - set1 | set2 or set1.union(set2) or set2.union(set1)
- Intersection - set1 & set2 or set1.intersection(set2) or set2.intersection(set1)
- Difference - set1 - set2 or set2 - set1 or set1.difference(set2) or set2.difference(set1)
- 
