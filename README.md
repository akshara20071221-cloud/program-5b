# program-5b
# 🧪 C Programming Lab
## 📘 Experiment No: 5b
### 🔹
**Date:** 25/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
To write a c program to swap two numbers using pointers.
---

## 🧠 ALGORITHM
1.Get two numbers as input from the user.
2.swap the values of two variables and print the result using printf() function
---

## 💻 PROGRAM
```
#include<stdio.h>
int main()
{
    int a,b;
    int *pa=&a,*pb=&b;
    scanf("%d %d",&a,&b);
    printf("m is %d, n is %d\n",*pa,*pb); 
    if(*pa!=*pb)
    {
        *pa=*pa+*pb;
        *pb=*pa-*pb;
        *pa=*pa-*pb;
    }
    printf("m is %d, n is %d",*pa,*pb);
}
```

## 🖼️ OUTPUT SCREENSHOT

<img width="610" height="333" alt="image" src="https://github.com/user-attachments/assets/fd8fb2ae-8245-4cca-a933-fc61e24fd87c" />


---

## ✅ RESULT
:Thus the C program to swap two numbers is successfully executed.
