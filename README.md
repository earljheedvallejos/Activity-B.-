# Activity-B.-
//B. Create a simple cashier program.
#include <iostream>
using namespace std;

int main(){

    int prod,num,n;

        cout << "=================================================="<<endl;
        cout << "\t  Earl'sShake\t||\t₱Price   "<< endl;
        cout << "                             "<< endl;
        cout << "1\tGatorade Shake\t||\t₱360   "<< endl;
        cout << "2\tCobra Shake\t||\t₱480      "<< endl;
        cout << "3\tVitamilk Shake\t||\t₱600   "<< endl;
        cout << "4\tRedhorse Shake\t||\t₱1998  "<< endl;
        cout << "                             "<< endl;
        cout << "==================================================";

        cout << endl<< "Enter Number: ";
        cin >> num;
        switch (num){
            case 1:
            cout << "Enter Payment: ";,
            cin >> n; 
            if (n>=360){
                prod=n-360;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 2:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=480){
                prod=n-480;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 3:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=600){
                prod=n-600;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            case 4:
            cout << "Enter Payment: ";
            cin >> n; 
            if (n>=1998){
                prod=n-1998;
                cout << "Change:₱ "<<prod<<endl;
            }
            else
                cout << "Invalid Payment"<<endl;
                break;
            }
       cout << "Programmed by: Earl Jheed Vallejos";

    return 0;
}
