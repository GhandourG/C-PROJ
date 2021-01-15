//# C-PROJ
//LEARNING C++
//------------------------------


#include<iostream>
#include<vector>
#include<string>
 
using namespace std;

int main(){
//declare three variable
    double Height , Weight , BMI;

//recevied Height
    cout << "Your Height Here(m):";
    cin >> Height;
//recevied width    
    cout << "Your Weight Here(kg):";
    cing >> Weight;
 
 //calculate BMI
    BMI = Weight / (Height * Height);
 
 //Print BMI
    cout << "Your BMI Is " << BMI << ";";
    
    }
    
    
    
    srand  (time (NULL) );
 
  int	coin = rand() % 2;
    
    
