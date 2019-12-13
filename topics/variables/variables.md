# Variables

- a variable is an abstraction for a memeory location
- allow progs to use meaningful names not memory addresses
- two properties:
  - type
  - value
- must be declared before used


```cpp
int y;  //type name;
y = 42; //type = value;

```



compile this [file](variables.cpp) with `g++ filename`

```cpp {.line-numbers}
#include <iostream>

using namespace std;

int main()
{
    int age {45};
    cout << age << endl;
}
```

- global variables 
  - [example](globalVar.cpp)



