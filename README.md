# -
/*
// Prg2-7
#include <iostream>
using namespace std;;

int main()
{
	// 변수 선언과 초기 
	int x = -1245;
	unsigned int y = 1245;
	unsigned int z = -2367;
	unsigned int t = 14.56;
	// 초기화된 값 출력 
	cout << x << endl;
	cout << y << endl;
	cout << z << endl;
	cout << t;
	return 0;
}

// Prg2-8
#include <iostream>
using namespace std;;

int main()
{
	// 변수 선언 
	int x;
	unsigned long int y;
	// 할당
	x = 1456;
	y = -14567;
	// 출력
	cout << x << endl;
	cout << y << endl;
	cout << 1234 << endl;
	cout << 143267L << endl;
	return 0; 
 }

 
// Prg2-9
#include <iostream>
using namespace std;;

int main()
{
	// char 자료형의 변수 선언과 초기화
	char first = 'A';
	char second = 65;
	char third = 'B';
	char fourth = 66;
	// 값 출력
	cout << "first의 값 : " << first << endl;
	cout << "second의 값 : " << second << endl;
	cout << "third의 값 : " << third << endl;
	cout << "fourth의 값 : " << fourth;
	return 0; 
}

// Prg2-10
#include <iostream>
using namespace std;;

int main()
{
	cout << "Hello\n";
	cout << "Hi\t friends." << endl;
	cout << "Buenos dias \bamigos." << endl; // 중간에 2칸 띄어쓰기
	cout << "Hello\Bonjour mes amis." << endl;
	cout << "This is a single quote\'." << endl;
	cout << "This is a double quote'." << endl;
	cout << "This is how to print a backslash \\.";
	return 0;
 } 
 

// Prg2-11
#include <iostream>
using namespace std;;

int main()
{
	// 변수 선언
	bool x = 123;
	bool y = -8;
	bool z = 0;
	bool t = -0;
	bool u = true;
	bool v = false; 
	// 값 출력
	cout << "x의 값: " << x << endl;
	cout << "y의 값: " << y << endl; 
	cout << "z의 값: " << z << endl;
	cout << "t의 값: "<< t << endl;
	cout << "u의 값: " << u << endl;
	cout << "v의 값: " << v << endl;
	return 0;
 } 

#include <iostream>
using namespace std;

int main()
{
	// 상수 선언
	const double PI = 3.14159;
	// 변수 3개 선언
	double radius;
	double perimeter;
	double area;
	// 반지름 입력받기
	cout << "원의 반지름 입력: ";
	cin >> radius;
	// 둘레와 면적을 계산하고 변수에 저장
	perimeter = 2 * PI * radius;
	area = PI * PI * radius;
	// 반지름, 둘레, 면적 출력
	cout << "반지름: " << radius << endl;
	cout << "둘레: " << perimeter << endl;
	cout << "면적: " << area; // 마지막 cout에는 endl;안써도 되는듯,, 
	return 0;  
}
*/


// Prg2-13
#include <iostream>
#include <string>
using namespace std; 

int main()
{
	// 변수 선언
	 string first;
	 string initial;
	 string last;
	 string space = " ";
	 string dot = ".";
	 string fullName;
	 // 이름, 이니셜, 성 입력받기
	 cout << "이름(first name) 입력하기: ";
	 cin >> first;
	 cout << "이니셜(initial) 입력하기: ";
	 cin >> initial;
	 cout << "성(last name) 입력하기: ";
	 cin >> last;
	 // 결합 연산자를 사용해서 문자열 연결
	 fullName = first + space + initial + dot + space + last;
	 // 전체 이름 출력
	 cout << "전체 이름(full name): " << fullName;
	  
	 return 0; 
}

