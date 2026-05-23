#include <iostream>
#include <cstring>

using namespace std;

struct songDetails {
    string title;
    string artist;
    int time;
    int year;
    string genre;

    };

void PrintSD(struct songDetails song){

    cout << "\n******************************\n";
    cout << "The title of the song is " << song.title << endl;
    cout << "the artist of the song is " << song.artist << endl;
    cout << "The length of the song is " << song.time << " seconds" << endl;
    cout << "The year of the song is " << song.year << endl;
    cout << "The genre of the song is " << song.genre << endl;

}

    void PrintYR(songDetails song, int yearRequest)
    {
        if (song.year == yearRequest)
        {
            PrintSD(song);
        }
    }

int main()
{
    struct songDetails song1;
    struct songDetails song2;
    struct songDetails song3;

    song1.title = "Love Me";
    song1.artist = "The 1975";
    song1.time = 222;
    song1.year = 2016;
    song1.genre = "Indie Pop";

    song2.title = "Tattoos Together";
    song2.artist = "Lauv";
    song2.time = 186;
    song2.year = 2020;
    song2.genre = "Pop";

    song3.title = "Hawai";
    song3.artist = "Maluma";
    song3.time = 200;
    song3.year = 2020;
    song3.genre = "Latin Pop";

    PrintSD(song1);
    PrintSD(song2);
    PrintSD(song3);

    cout << "\n*********************************************************\n";


    int yearRequest;

    cout << "What year do you want to see for a list of songs?" << endl;
    cin >> yearRequest;

    PrintYR(song1, yearRequest);
    PrintYR(song2, yearRequest);
    PrintYR(song3, yearRequest);

    return 0;
}
