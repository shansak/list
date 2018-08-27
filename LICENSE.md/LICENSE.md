#include<iostream>
#include<list>
using namespace std;

int main()
{
    list<int>p{23,12,23,45,56,67};
    p.sort();
    p.push_front(1);
    p.push_back(100);
    p.pop_back();
    p.pop_front();
    p.reverse();
    p.remove(45);

    list<int>::iterator t=p.begin();
    while(t!=p.end()){
            cout<<*t<<endl;
             t++;



    }
    cout<<p.size();
}


