#include <iostream>

using namespace std;

int main()
{
     int x,y,res=1; int i,n=6,p; for(i=1;i<10;i++)
     {
         x=i; y=10; while(y!=0) { res*=x; p=res; if(res>11)
         {
             while(p>11)
             {
                 p-=10;
                 p--;
             }
             res=p;
         }
            y--;
            cout<<"  "<<res;
     }
     cout<<endl<<endl;
     }
}

