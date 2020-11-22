***********************************************************EXAMPLE OF STACKS CONTAINS ERRORS **************************************************************************
#include <iostream>

using namespace std; 

struct Node {
	int data;
	struct Node * next;	
	int sMAX_STACK=10;
};



void push(struct Node **top,int x){ //the function of push. It contains a top pointer and and x data.
//allocate the new node in the heap:

struct Node* newNode=NULL;
newNode = new Node;

//check the stack is full or not. If it is not full insert a new node into it: 

if(!newNode){
	
	cout<<"Heap is overflow"<<endl;
	return false;
}
//set the data in the allocated node: 
newNode->data=x;
newNode->next=top;
//update the top pointer: 
*top=newNode; //After that, top shows the new node. The last inserted node.
sMAX_STACK++;
}

int isEmpty(struct Node * top){
	
	if (top=-1){
		return false;
	}
int top(struct Node *top){
	if(!isEmpty(top)){
		return top->data;
	}
	
void pop(struct Node **top){
	struct node * newNode;
	if (*top=-1){
		return false;
	else 
	*top=newNode; // the top shows the new node that will be deleted
	*top=top->next;//the new top pointer shows the current top's next.
	}	
	sMAX_STACK--;
}		
	delete (newNode);
}
	
	int main(){
		
	push(&top,1); //it gives 1 to new top address.
	push(&top,2);
	push(&top,3);
	
	cout<<"The pushed data is:"<<top(top)<<endl;	
		
	pop(&top); //it deletes the top of the stack.
	pop(&top);
	pop(&top);	
		
		
		
	}	
}		
}
