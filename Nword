#include <iostream>

using namespace std;

void printNTimes(int times, char c){
	for(int i=0;i<times;i++){
		cout << c;
	}
}

int main(){

	// Read from stdin
	int line;
	cin >> line;

	for(int i=0;i<line;i++){
		// It consist of 2 V
			printNTimes(3,'*');
			printNTimes(i,' ');
			printNTimes(3,'*');
			printNTimes(line-i-1,' ');
			printNTimes(3,'*');
			cout << "\n";
	}
	return 0;
}