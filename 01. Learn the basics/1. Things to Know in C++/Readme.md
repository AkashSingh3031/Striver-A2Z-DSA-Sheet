## `1. Basic I/O`

```cpp
#include<bits/stdc++.h>
using namespace std;

int main() {
  cout << "Name: " << "Akash Singh";
  return 0;
}
```
<table>
  <td> OUTPUT: </td> <td> Name: Akash Singh </td>
</table>

```cpp
#include<bits/stdc++.h>
using namespace std;

int main() {
  int x, y;
  cout << "Enter value of x and y = ";
  cin >> x >> y;
  cout << "Value of x = " << x << " and y = " << y;
  return 0;
}
```
<table>
  <td> INPUT: </td> <td> Enter value of x and y = 10 20</td>
</table>
<table>
  <td> OUTPUT: </td> <td> Value of x = 10 and y = 20</td>
</table>

## `2. Data Types`

```cpp
#include<bits/stdc++.h>
using namespace std;

int main() {
  // int, long, long long, float, double
  int i;
  long l;
  long long ll;
  float f;
  double d;
  
  // string, getline
  string s;
  string g;
  
  // char
  char c;
  
  cout << "Enter value of int:i, long:l, long long:ll, float:f, double:d, getline string:s, string:g and char:c = " << endl;
  cin >> i >> l >> ll >> f >> d >> s >> g >> c;
  cout << "Value of int i = " << i << endl << " and long l = " << l << endl << " and long long ll = " << ll << endl << " and float f = " << f << endl << " and double d = " << d << endl << " and single string s = " << s << endl << " and space seprated string g = " << g << endl << " and char c = " << c;
  return 0;
}
```
<table>
  <td> INPUT: </td> <td> Enter value of int:i, long:l, long long:ll, float:f, double:d, string:s, getline string:g and char:c = <br> 10 <br> 20 <br> 5000 <br> 5.5 <br> 5000.5 <br> Akash <br> Akash Singh <br> A </td>
</table>
<table>
  <td> OUTPUT: </td> <td> Value of int i = 10 <br> and long l = 20 <br> and long long ll = 5000 <br> and float f = 5.5 <br> and double d = 5000.5 <br> and single string s = Akash <br> and space seprated string g = Akash Singh <br> and char c = A</td>
</table>
