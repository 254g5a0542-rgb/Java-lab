## Experiment 1

## Experiment 1A

## TITLE: Display the primitive datatypes

---

## SOURCE CODE: primitive datatypes

```

public class task1a {
byte b;
int i;
double dou;
boolean bo;
char c;
float f;
long l;
short s;
public static void main(String[] args){
task1a t=new task1a();
System.out.println("default value of byte is:"+t.b);
System.out.println("default value of int is:"+t.i);
System.out.println("default value of double is:"+t.dou);
System.out.println("def val of boolean is:"+t.bo);
System.out.println("def val of char is:"+t.c);
System.out.println("def val of float is:"+t.f);
System.out.println("def val of long is:"+t.l);
System.out.println("def val of short is:"+t.s);
}
}
```

## output
![WhatsApp Image 2026-01-22 at 2 21 48 PM](https://github.com/user-attachments/assets/78cfe9f0-ee15-4c2b-a42e-030b58a1ac5c)




## EXPERIMENT 1B

## TITLE: Display the Quadratic Equations

---

## SOURCE CODE: Quadratic Equations

```
import java.util.Scanner;
public class quad
{
public static void main(String[] args) {
Scanner s=new Scanner(System.in);
System.out.println("enter coeff of a:");
double a=s.nextDouble();
System.out.println("enter coeff of b:");
double b=s.nextDouble();
System.out.println("enter coeff of c:");
double c=s.nextDouble();
double discriminant=b*b-4*a*c;
if(discriminant>0)
{
double root1=(-b+Math.sqrt(discriminant))/(2*a);
double root2=(-b-Math.sqrt(discriminant))/(2*a);
System.out.println("the roots are real and distinct");
System.out.println("root1:"+root1);
System.out.println("root2:"+root2);
}
else if(discriminant==0)
{
double root=-b/(2*a);
System.out.println("the root is real and equal");
System.out.println("root:"+root);
}
else
{
double realpart=-b/(2*a);
double imaginarypary=Math.sqrt(-discriminant)/(2*a);
System.out.println("the roots are complex and distinct");
System.out.println("root1:" + realpart + "+" + imaginarypart + "i");
System.out.println("root2:" + realpart + "-" + imaginarypart + "i");
}
}
}
```


## OUTPUT
![WhatsApp Image 2026-01-22 at 2 21 47 PM](https://github.com/user-attachments/assets/b4286288-6322-4a2d-ae67-e23dc9142e37)







