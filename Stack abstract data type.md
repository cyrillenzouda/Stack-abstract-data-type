

```python
class stack:
    def __init__(self):
        self.data=[]
        
    def push(self, data):
        self.data.append(data)
    
    def size(self):
        return len(self.data)
        
    def pop(self):
        data =self.data[-1]
        del self.data[-1]
        return data
    
    def peek(self):
        return self.data[-1]
        
newstack=stack()
newstack.push(1)
newstack.push(2)
newstack.push(3)
newstack.push(4)
newstack.size()
newstack.pop()
newstack.size()
newstack.peek()

```




    3


