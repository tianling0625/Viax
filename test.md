##201801-CS300-聊天机器人workshop-王天宇-课前自测

###Problem A:
```{python}
class Robot(object):
    def __init__(self, name):
        self.name = name
        
    def __train(self):
        pass
    def get(self,input_message):
        self.input_message = input_message
        
def main():
    print("hello world")
        
if __name__ == "__main__":
    main()
```
###Problem B:
```{python}
def print_array(name, a):
    Nice = name + ": "
    for x in a:
        Nice += ("%s, " % x)
    print(Nice[:-2] + ".")
    
#eg:
    
print_array("Wut", [3,2,7])
```

###Problem C:
```{python}
import time
def print_process(current_step, total_step):
    if current_step > total_step or current_step < 0:
        print("Oops!")
        
    else:
        persentage = "%.1f" % (current_step * 100 / total_step)
        grid = int(current_step * 10 / total_step)
        print("#"*grid+" "*((10-grid)+6-len(persentage))+persentage+"%")
        time.sleep(0.1)
        print("012345678901234567890")
        print("|=========|=========|  ruler" )

#eg:
        
print_process(100,100)
```
