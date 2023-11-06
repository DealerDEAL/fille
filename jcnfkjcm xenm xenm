#include <iostream>
#include <fstream>
#include <stdio.h>
#include <vector>
#include <stdlib.h> 
#include <time.h>
#include <iomanip>
#include <cstring>

using namespace std;

 class Verticals{
    public:
    string vertical_coordinates;
    /*void Verticals_print(ifstream &file, char* determinant_tr){
        string s;
        int i = 0;
        while(i != 40){ // пока не достигнут конец файла класть очередную строку в переменную (s)
        getline(file, s);
            if(s[0] == determinant_tr[0]){
                if(s[1] == ' ') {
                    part[0] == s;
                    while(i < 4){
                        p = strtok(s, " ");
                        if(p[0] == '-' || p[0] == '1'){
                            strcpy(w, p);
                        }
                        i++;
                    }
                }
            }
            cout << s << endl;
            
        }
    }*/
 };
 class normali{
     double a, b, c;
 };
 class tex_cord{
     double x, y;
 };
 class facels{
     double A[4], B[4], C[4];
 };
 class count{
     public:
     unsigned int normal_count;
     unsigned int facels_count; 
     unsigned int tex_cord_count; 
     unsigned int verticals_count;
     count() : normal_count(0), facels_count(0), tex_cord_count(0), verticals_count(0) {}
     void fount(ifstream &file, char* determinant_tr){
         string s;
          while(getline(file, s)){ // пока не достигнут конец файла класть очередную строку в переменную (s)
            cout << s << endl; // выводим на экран
           if (s[0] == determinant_tr[0]) {
               if(s[1] == ' ') {
                   verticals_count++;
                   //strtok(, " ");
                   
               }
               if(s[1] == 't') {
                   tex_cord_count++;
               }
               if(s[1] == 'n') {
                   normal_count++;
               }
           }
           if(s[0] == determinant_tr[1]) {
               facels_count++;
           }
           
        }
         
         cout << tex_cord_count;
        // while(i != 40){
        //     fgets(bufer, sizeof(bufer), stream);
        //     if(bufer[0] == 'v'){
        //         verticals_count++;
        //     }
        //     if(bufer[0] == determinant_tr[1]){
        //         tex_cord_count++;
        //     }
        //     if(bufer[0] == determinant_tr[2]){
        //         normal_count++;
        //     }
        //     if(bufer[0] == 'f'){
        //         facels_count++;
        //     }
        //     i++;
        // }
        // cout << verticals_count;
        // cout << tex_cord_count;
        // cout << normal_count;
        // cout << facels_count;
    }
};

/*void print_v(Verticals.x, Verticals.y, Verticals.z){
    while(i != 40){
        fgets(bufer, sizeof(bufer), stream);
        if(bufer)
    }
    
}*/


int main()
{
   
    ifstream file("cube.obj");
    int i = 0;
    FILE *stream;
    stream = fopen("cube.obj", "r");
    char bufer[256];
    bufer[0] = 'g';
    vector<string> determinant;
    char determinant_tr[8];
    string y;
    for(int i = 0; i<2; i++){
        cin >> y;
    determinant.push_back(y);   
    }
    determinant_tr[0] = determinant[0][0];
    determinant_tr[1] = determinant[1][0];
    count k;
    k.fount(file, determinant_tr);
    Verticals j[8];
    i = 0;
    while(bufer[0] != 'v'){
        fgets(bufer, sizeof(bufer), stream);
        i++;
        cout << i;
    }
    char* v;
    i = 0;
    while(i = k.verticals_count){
        v = strtok(bufer, " ");
        while (v) { 
        //cout << v << "\n" << endl; 
        v = strtok(NULL," "); 
        j[i].vertical_coordinates = v;
        cout << "\n" << j[i].vertical_coordinates;
        } 
    }

    //determinant_tr[2] = determinant[2][0];
    //determinant_tr[3] = determinant[3][0];
    //cout << c.normal_count;
    //while(i<sizeof(bufer)){
    //    std::cout << bufer[i] << std::endl;
    //    i++;
    //}

    return 0;
}
