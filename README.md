# right-shift_assignment-and-left-shift_assignment
determining the value of x

#include <iostream>
using namespace std;
 
int main() {
    int x = 100;
    //right-shift assignment
    x >>= 3;
    cout << "x : " << x << endl;
}
  /*output:
  
  x:12 */
  
#include <iostream>
using namespace std;
 
int main() {
    int x = 10;
    //left-shift assignment
    x <<= 1;
    cout << "x : " << x << endl;
}
  /*output:
  
  x:20 */
