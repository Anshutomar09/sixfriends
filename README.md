# sixfriends
New repo
ques=six friends go on a trip and are looking for accommodation. After looking for hours, they find a hotel which offers two types of rooms — double rooms and triple rooms. A double room costs Rs. XX, while a triple room costs Rs. YY.

The friends can either get three double rooms or get two triple rooms. Find the minimum amount they will have to pay to accommodate all six of them
#include <stdio.h>

int main(void) {
	// your code goes here
	int t,x,y,a,b;
	scanf("%d", &t);
	
	while(t--){
	    scanf("%d\t%d", &x,&y);//x=doublebedroom,y=triplebedroom
	    a=x+x+x;
	    b=y+y;  
	    if(a<b){
	    printf("%d\n", a);
	    }
	    else{
	        printf("%d\n", b);
	    }
	}
	return 0;
}

