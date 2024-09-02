# Traverse_tuple
#Various methods to traverse in tuples

newTuple =("a", "b", "c", "d", "e")

def search_tuple(p_tuple, element):
    for index, value in enumerate(p_tuple):
        if value == element:
            return (f"found {element} at index {index}")
        
    return "Element not found"


result = search_tuple(newTuple, "c")
print(result)
