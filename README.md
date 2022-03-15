# Program-to-sum-first-n-natural-numbers-in-C-using-For-loop.
Program to sum first n natural numbers in C++ using For loop.
#include <iostream>
using namespace std;
int main()
{
     int n, count, sum = 0;
    cout<<"Nhập vào n (số lượng phần tử đầu tiên cần tính tổng): ";
    cin>>n;
    cout<<"Các số cần tính là: ";
    for(count=1; count <= n; count++)
    {
        sum = sum + count;
        cout<<count<<"\t";
    }
    cout<<endl<<"Tổng "<<n<<" đầu tiên là: "<<sum;
    cout<<"\n-----------------------------------\n";
    cout<<"Chương trình này được đăng tại Freetuts.net";
}
