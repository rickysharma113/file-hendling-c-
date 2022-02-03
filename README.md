#include <iostream>
#include <fstream>
#include <string>
using namespace std;
int main(){
    string st1="Good morning everyone.\n";
    string st2="My name is ricky sharma.\n";
    string st3="I belong to jaipur \n";
    string st4="I have recently passed out 12th class.\n";
    string st5="I am currently getting into RNS It Solutions.\n";
    string st6="I have seven members in my family.\n";
    string st7="My Grandfather name is mr hanuman shay sharma.\n";
    string st8="My grandmother name is mrs rameshwari sharma.\n";
    string st9="My father name is mr anil sharma and my father is a farmer.\n";
    string st10="my mother name is sunita  sharma and my mother is a teacher.\n";
    string st11="I have a brother\n";
    string st12="My hobbies are watching movies and playing games.\n";
    string st13="I like to eat fast food and dislike non-veg.\n";
     string st14="Thanking you.\n";
    
    ofstream obj("demo.txt");
    obj<<st1;
    obj<<st2;
    obj<<st3;
    obj<<st4;
    obj<<st5;
    obj<<st6;
    obj<<st7;
    obj<<st8;
    obj<<st9;
    obj<<st10;
    obj<<st11;
    obj<<st12;
    obj<<st13;
    obj<<st14;
    obj.close();
    return 0;
}
