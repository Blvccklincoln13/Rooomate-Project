#Roommate Details
- *Name:* Eric Mbugua Jones  
- *Age:* 19 years  
- *Hobbies:* Zip lining, playing guitar  
- *Personality:* Kind and shy  

#Files Included
- roommate.cpp — C++ version  
- roommate.py — Python version  

#Purpose
This assignment was created for a programming task requiring code in both C++ and Python to describe a roommate.


 ROOMMATE.CPP
 #include <iostream>
using namespace std;

int main() {
    // Roommate details
    string name = "Eric Mbugua Jones";
    int age = 19;
    string hobbies = "Zip lining and playing guitar";
    string personality = "Kind and shy";

    cout << "--- Roommate Information ---" << endl;
    cout << "name: " << name << endl;
    cout << "Age: " << age << endl;
    cout << "Hobbies: " << hobbies << endl;
    cout << "Personality: " << personality << endl;

    cout << "\nMy roommate is " << name << ". He is "
         << age << " years old, enjoys " << hobbies
         << ", and he is very " << personality << "." << endl;

    return 0;
}


ROOMMATE PY

# Roommate details
name = "Eric Mbugua Jones"
age = 19
hobbies = "Zip lining and playing guitar"
personality = "Kind and shy"

print("--- Roommate Information ---")
print("Name:", name)
print("Age:", age)
print("Hobbies:", hobbies)
print("Personality:", personality)

print(f"\nMy roommate is {name}. He is {age} years old, enjoys {hobbies}, and he is very {personality}.")
