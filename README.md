# pattern

**1)DIAMOND:**

<img src="http://drive.google.com/uc?export=view&id=1GmEX_YfsEk-Qi2jgvMzE3u43yNvRwZKB" width="100"/>
  

```
#include <iostream> 
using namespace std;  
int main() 
{ 
    int n ; 
	cin>>n;  //here n=6 fo image shown above
 int i, j, k = 0; 
    for (i = 1; i <= n; i++)
    { 
        
        for (j = i; j < n; j++) { 
            cout << " "; 
        } 
    
        while (k != (2 * i - 1)) { 
            if  (k==0||k == 2 * i - 2) 
                cout << "*"; 
            else
                cout << "*"; 
            k++; 
           
        } 
		
        k = 0; 
        cout << endl;
    } 
	for (i = 2; i <= n; i++) { 
     
        for (j = 1; j < i; j++) { 
            cout << " "; 
        } 
  
        
        for (j = 1; j <= (n * 2 - (2 * i - 1)); j++) { 
  
            if (i == 1 || j == 1 || j == (n * 2 - (2 * i - 1))) { 
                cout << "*"; 
            } else { 
                cout << "*"; 
            } 
			
        
        } 
        cout << endl; 
    } 
  
} 
```

**2)Hollow Diamond:**


<img src="http://drive.google.com/uc?export=view&id=1c1LRi_ts43y2QTIa3mqrgvHK4kFJCAi2" width="100"/>


```
#include <iostream> 
using namespace std; 
int main() 
{ 
    int n ; //here n=6 for above picture
	  cin>>n;
    int i, j, k = 0; 
    for (i = 1; i <= n; i++)
    { 
        
        for (j = i; j < n; j++) { 
            cout << "*"; 
        } 
    
        while (k != (2 * i - 1)) { 
            if (k == 0 || k == 2 * i - 2) 
                cout << "*"; 
            else
                cout << " "; 
            k++; 
            ; 
        } 
		for (k = 1; k < (n+1)-i; k++) 
		{ 
            cout << "*"; 
		}
        k = 0; 
        cout << endl;
    } 
	for (i = 2; i <= n; i++) { 
     
        for (j = 1; j < i; j++) { 
            cout << "*"; 
        } 
  
        
        for (j = 1; j <= (n * 2 - (2 * i - 1)); j++) { 
  
            if (i == 1 || j == 1 || j == (n * 2 - (2 * i - 1))) { 
                cout << "*"; 
            } else { 
                cout << " "; 
            } 
			
        
        } 
       for (k = 1; k < i; k++) { 
            cout << "*"; 
	   }
        cout << endl; 
    } 
  
} 
```
**3)Hollow Diamond(type2)**



<img src="http://drive.google.com/uc?export=view&id=1q-dKbxjnwR0-tvMOspF3ObRM1xFCaHWF" width="100"/>

```
#include <iostream> 
using namespace std; 
void printPattern(int); 
int main() 
{ 
    int n ; 
	cin>>n;
  
    printPattern(n); 
} 
void printPattern(int n) 
{ 
    int i, j, k = 0; 
    for (i = 1; i <= n; i++)
    { 
        
        for (j = i; j < n; j++) { 
            cout << " "; 
        } 
    
        while (k != (2 * i - 1)) { 
            if (k == 0 || k == 2 * i - 2) 
                cout << "*"; 
            else
                cout << " "; 
            k++; 
            ; 
        } 
	
        k = 0; 
        cout << endl;
    } 
	for (i = 2; i <= n; i++) { 
     
        for (j = 1; j < i; j++) { 
            cout << " "; 
        } 
  
        
        for (j = 1; j <= (n * 2 - (2 * i - 1)); j++) { 
  
            if (i == 1 || j == 1 || j == (n * 2 - (2 * i - 1))) { 
                cout << "*"; 
            } else { 
                cout << " "; 
            } 
			
        
        } 
      
        cout << endl; 
    } 
  
} 
```
**4)half diamond/ Christmas tree:**




<img src="http://drive.google.com/uc?export=view&id=1ZcyTaU9PSOa6ZmSuj8zROMzvxj4mBQQ_" width="100"/>




```
#include <iostream> 
using namespace std; 
void printPattern(int); 
int main() 
{ 
    int n ; 
	cin>>n;
  
    printPattern(n); 
} 
void printPattern(int n) 
{ 
    int i, j, k = 0; 
    for (i = 1; i <= n; i++)
    { 
        
        for (j = i; j < n; j++) { 
            cout << " "; 
        } 
    
        while (k != (2 * i - 1)) { 
            if (k == 0 || k == 2 * i - 2) 
                cout << "*"; 
            else
                cout << "*"; 
            k++; 
            ; 
        } 
	
        k = 0; 
        cout << endl;
    } 
	
  
} 
```


