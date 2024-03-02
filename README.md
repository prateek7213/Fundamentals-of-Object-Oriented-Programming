#include<iostream>
using namespace std;
class abc{
    int num,count=0;
    public:
    void get()
    {
        
        while(1)
        {
            cout<<"enter a number "<<endl;
            cin>>num;
            if(num%8==0)
            {
                count++;
            }
            else {
                cout<<"valid divisible count are "<<count<<endl;
            break;
             }
           
        }
    }

};
int main()
{
    abc obj;
    obj.get();
    return 0;
}
