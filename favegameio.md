//io Console Application for Favorite Video Game

#include <iostream>
using namespace std;

int main()
{
    int year;
    string game;
    string console;
    
    // Console Selections
    string mygame = "Pong";
    int myyear = 1972;
    string myconsole = "(Atari)";


    // User io interaction (Data Collection)
    cout << "\n Input your favorite video game:";
    cin >> game;
    cout << "\n Enter the gaming console (use round brackets):";
    cin >> console;
    cout << "\n Input the year the game was created:";
    cin >> year;
    

    // Console Response 1
    cout << "\n\n My favorite video game is:" ;
    cout << "\n\n";
    cout << mygame;
    cout << myconsole;
    cout << myyear;
   

    cout << "\n\n Your favorite video game is:";
    cout << "\n\n";
    cout << game;
    cout << console;
    cout << year;
    

    //Console Response 2

    cout << "\n\n I have superior taste in video games and I hope none of your dreams come true in life.";
    cout << "\n\nDisrespectfully, \n\n Fave Game io";



    system("pause>0"); //Omits garbage text from bottom of Console


    return 0;

    
}
