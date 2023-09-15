// Ques : Take 2 integers input and print the greatest of them.
#include<iostream>
using namespace std;
int main()
{
    int a,b;
    cout<<"Enter First Number : ";
    cin>>a;
    cout<<"Enter Second Number : ";
    cin>>b;
    if(a>b) cout<<"a is greatest";
    else cout<<"b is greatest";
}

// Ques : Given the radius of the circle predict whether numerically area of this circle is larger than the circumference or not.
#include<iostream>
using namespace std;
int main()
{
    cout<<"Enter Radius :";
    float Radius,Area,cirm;
    cin>>Radius;
    Area=Radius*3.14*Radius;
    cout<<"Area of circle is "<<Area<<endl;
    cirm=2*3.14*Radius;
    cout<<"cirm of the circle is "<<cirm<<endl;
    if(Area>cirm)
    cout<<"Area of circle is larger";
    else
    cout<<"cirm of circle is larger";    
}

//Ques : Given the length and breadth of a rectangle, write a program to find whether numerically the area of the rectangle is greater than its perimeter.

#include<iostream>
using namespace std;
int main()
{
    cout<<"Enter Length : ";
    float Length,Breadth,Area,Perimeter;
    cin>>Length;
    cout<<"Enter Breadth : ";
    cin>>Breadth;
    Area=Length*Breadth;
    cout<<"Area of The Rectangle is : "<<Area<<endl;
    Perimeter=2*(Length * Breadth);
    cout<<"Perimeter of The Rectangle is : "<<Perimeter<<endl;
    if(Area>Perimeter)
    cout<<"Area of Reactangle is Greater";
    else
    cout<<"Perimeter of Reactangle is Greater";
}

//Ques : Write a program to input sides of a triangle and check whether a triangle is equilateral, scalene or isosceles triangle.

#include<iostream>
using namespace std;
int main()
{
    int a,b,c;
    cout<<"Enter 1st Side :";
    cin>>a;
    cout<<"Enter 2nd Side :";
    cin>>b;
    cout<<"Enter 3rd Side :";
    cin>>c;
    if(a==b)
    {
        if(b==c)
        cout<<"Triangle is Equilateral";
    }
    if(a==b || a==c || b==c)
    {
    cout<<"Triangle is isosceles";
    }
    else
    {
       cout<<"Triangle is scalene";
    }

    
}

// Ques : If the marks of A, B and C are input through the keyboard, write a program to determine the student scoring least marks.

#include<iostream>
using namespace std;
int main()
{
    int a,b,c;
    cout<<"Enter Marks1 : ";
    cin>>a;
    cout<<"Enter Marks2 : ";
    cin>>b;
    cout<<"Enter Marks3 : ";
    cin>>c;
    if(a<b)
    {
        if(a<c)
        {
            cout<<"Marks1 is least";
        }
    }
    if(b<a)
    {
        if(b<c)
        {
            cout<<"Marks2 is least";
        }
    }
    if(c<a)
    {
        if(c<b)
        {
            cout<<"Marks3 is least";
        }
    }
        
}

//Given a point (x, y), write a program to find out if it lies on the x-axis, y-axis or at the origin, viz. (0, 0)

#include<iostream>
using namespace std;
int main()
{
    float x,y;
    cout<<"Enter the coordinates of x-y : ";
    cin>>x>>y;
    if(x==0 && y==0)
    cout<<"lies at origin";
    if(x>0 && y==0)
    cout<<"lies on x-axis";
    if(y>0 && x==0)
    cout<<"lies on y-axis";
}
