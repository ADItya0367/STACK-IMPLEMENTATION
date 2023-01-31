# STACK-IMPLEMENTATION
Stack is implemented in this repository , we will see how an element is being removed , inserted  in the stack which follows LIFO principal 


#include <iostream>
#include <stack>
using namespace std;
int main() {
	stack<int> stack;
	stack.push(21);// The values pushed in the stack should be of the same data which is written during declaration of stack
	stack.push(22);
	stack.push(24);
	stack.push(25);
	int num=0;
	stack.push(num);
	stack.pop();
	stack.pop();
	stack.pop();

	while (!stack.empty()) {
		cout << stack.top() <<" ";
		stack.pop();
	}
}

GIVE ME A STAR !!
