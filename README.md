//# C-PROJ
//LEARNING C++
//------------------------------

#include<iostream>
#include<vector>
#include<string>
 
using namespace std;

int main(){

    double Height , Weight , BMI;
    
    cout << "Your Height Here(m):";
    cin >> Height;
    
    cout << "Your Weight Here(kg):";
    cing >> Weight;
    
    BMI = Weight / (Height * Height);
    
    cout << "Your BMI Is " << BMI << ";";
