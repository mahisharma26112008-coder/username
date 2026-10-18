# username


#include <iostream>
using namespace std;

int main() {
    string username, password;

    cout << "Enter username: ";
    cin >> username;

    cout << "Enter password: ";
    cin >> password;

    if (username == "Mahi" && password == "1234") {
        cout << "Login successful";
    }
    else if (username != "Mahi") {
        cout << "Username incorrect";
    }
    else {
        cout << "Password incorrect";
    }

    return 0;
}
