# c++11patterns
//c++ program to execute simole pattern


#include<iostream.h>
#include<conio.h>
void main()
{
int i,j;
for(i=1;i<=6;i++)
{
int s=1;
   for(j=1;j<=11;j++)
    {   if(j>=7-i&&j<=5+i&&s)
          {    cout<<"*";
                s=0;    
           }
       else 
       {    cout<<" ";
            s=1;
        }
    }
   cout<<"\n";
   }
getch();

}
