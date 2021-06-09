# HW2
1. 請寫一個程式可以印出指定數量的 * 號

   例如： star(5) 會印出 5 個 * 號

   star(5)

2. 請寫一個函數可以印出 a..b 之間的所有整數

   例如： between(3,8) 會印出

   3 4 5 6 7 8

3. 請寫一個函數 primeBetween(a,b) 可以印出 a..b 之間的質數

   例如 primeBetween(3,15)

   3 5 7 11 13

   ## 作業 1
```
function star(n){
    for (var i=0;i<n;i++)
    console.log('*')
}

star(5)
```
執行結果
```
*
*
*
*
*
```

## 作業 2
```
function between(a,b){
    for(var a;a<=b;a++)
    console.log(a);
}
between(3,8)
```
執行結果
```
3
4
5
6
7
8
```
## 作業 3
```
function isprime(n){
    for (var i=2; i<n;i++){
    if(n%i==0){
        return false;
    }
};
    return true;
}
function prime(x,y){
    for (var j=x; j<y;j++)
    if(isprime(j)){
        console.log(j)
    }
}
prime(3,15)
```
執行結果

```
3
5
7
11
13
```