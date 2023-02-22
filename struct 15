#include <stdio.h>
struct emp
{
    int id;
    char name[36];
    int sal;
}
e1 ={101, "Raj", 12500};
e2 ={102, "Teja"};
void main ()
{
        struct emp e3, e4, e5, e6;
        e3.id = 103;
        e3.name = Rajesh;  //Error
        e3.name = "Rajesh";
        strcpy (e3.name, "Rajesh");
        e3.sal = 14000;
        e4 = e3 + 1;  //error
        e4 = e3.id + 1;  //Error
        e4.id = e3.id + 1;  //yes
        e4.name = e3.name;  //Error
        strcpy (e4.name, e3.name);
        e4.sal = e1 + e2;  //Error
        e4.sal = e1.sal + e2.sal; //yes
        e5 = e4;
        //We can assign one structure variable to another structure variable of same type.e4 == e5; //Error
        e4.id = e5.id;  //yes
        e3.name > e4.name;  //error
        strcmp (e3.name, e4.name);
        e3.sal < e2.sal;  //yes
}
