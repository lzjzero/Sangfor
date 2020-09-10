时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 32M，其他语言64M
  
  
请实现list_sort，使用冒泡法将head指向的链表按val值大小排成升序 

struct node { 
    int val; 
    struct node *next; 
}; 
void list_sort(struct node *head) 
{ 
} 
  
  
输入描述:

第一行为数据个数 第二行为输入的数据，以空格进行分隔
  
  
输出描述:

输出head指向的链表数据，以空格分隔
  
  
输入例子1:

12

10 22 2 5 9 8 1 33 4 6 7 9
  
  
输出例子1:

1 2 4 5 6 7 8 9 9 10 22 33
