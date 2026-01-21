## Pointer
- variable that address the memory of another variable
```
// e.g.,
int a = 10;
int* b = &a;
int** c = &b; //points to another pointer
int*** d =
```

### Function Parameters?
- **Pass by Reference** (pointers) -the address (i.e., pointer) the being pointed is being passed (perfect if you wanna modify it or it's an array)
```
int addy(int *a, int *b){
return 
}
```
- **Pass by Value** - the value itself is being passed
``` 
//e.g,
int add(int a, int b);
int main(){
int x = 20, y = 10
sum = add(x,y);
printf("%d", sum);
}

add(int a, int b){

return a + b;

}
```