#include<iostream>
#include<ctime>//生成随机数字.
using namespace std;
int main() {
	srand((unsigned int)time(NULL));  //生成随机数字.
	int num = rand() % 100 + 1;
}
