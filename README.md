# details_function:
Nested functions:function inside another function is nested function
def outer():
    print('This is outer function')
    def inner():
        print('Inner function')
    inner()
outer()
function referencing: using outer we are referring to inner
def outer():
    print('This is outer function')
    def inner():
        print('Inner function')
    return inner
o = outer()
print(o)
o()
o() # o in an instance of inner
