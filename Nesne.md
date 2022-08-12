### NESNE ÜRETME(UCGEN KENARLARI VE YUKSEKLİK ALIP ALAN VE CEVRE HESAPLAMA)

```
package ucgen;

import java.util.Scanner;

public class ucgen {
    public double h;
    public double a;
    public double b;
    public double c;
    public double alan(){
        return c*h/2;
    }
    public double cevre(){
        return a+b+c;
    }
   
    public static void main(String[] args) {
        ucgen u=new ucgen();
        Scanner input=new Scanner(System.in);
        double a,b,c,h;
        System.out.println("a,b,c,h sirasıyla giriniz:");
        a=input.nextDouble();
        b=input.nextDouble();
        c=input.nextDouble();
        h=input.nextDouble();
        
        u.a=a;
        u.b=b;
        u.c=c;
        u.h=h;
        System.out.println("alan:"+u.alan());
        System.out.println("cevre:"+u.cevre());
        
    }
    
}
```
