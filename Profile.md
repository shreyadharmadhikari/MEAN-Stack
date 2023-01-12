## This is second branch
## This is just for demo purpose.


```

#include <iostream> 
using namespace std;
 
int main() {
   string str = "And still, I rise.";
   char rev[str.length()];
 
   for (int index = 0, len = str.length(); (index < len); index++) {
      rev[index] = str[len-1-index];
   }
 
   cout << rev << endl;
}

```
