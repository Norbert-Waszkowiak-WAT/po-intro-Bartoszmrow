#include <iostream>

using namespace std;
 
class Point {

public:

    int x;

    int y;
 
    void print() {

        cout << "(" << x << ", " << y << ")" << endl;

    }

};
 
int main() {

    Point p1;

    p1.x = 3;

    p1.y = 5;
 
    Point p2;

    p2.x = -2;

    p2.y = 10;
 
    Point p3;

    p3.x = 0;

    p3.y = 0;
 
    p1.print();

    p2.print();

    p3.print();
 
    return 0;

}
 