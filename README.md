# Uploading-an-existing-file#include <iostream>
#include <string>
using namespace std;

int main(){
	string id_user = "andi123";
	string password = "rahasia123";
	string input_id, input_pass;
	
	cout << "Masukkan ID: "; 
	cin >> input_id;
	cout << "Masukkan Password: ";
	cin >> input_pass;
	
	if (input_id == id_user && input_pass == password) 
	    cout << "Login berhasil!";
	else
	    cout << "Login gagal";
	}
