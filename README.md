#include <iostream>
#include <string.h>

using namespace std;

//Global variables
string POKEMON_1 = "Charizard";
string POKEMON_2 = "Pikachu";

//Pokemon HP
int hp1 = 60;
int hp2 = 65;



//Function Prototypes
void displayHPBar(int);


int main(){
    displayHPBar(hp1);
    
    return 0;
}

//Function Definitions
void displayHPBar(int hp){
    
    for(int x=hp;x>0;x-=5){
        cout << "|";
    }
    cout << endl;
}
