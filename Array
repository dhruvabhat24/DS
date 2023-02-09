#include<stdio.h>
int a[20];
int n,elem,i,pos;
void create();
void insert();
void delete();
void display();
void main()
{
    int choice;
    while(1)
    {
        printf("\nMENU\n");
        printf("\n1.CREATE\n");
        printf("\n2.INSERT\n");
        printf("\n3.DELETE\n");
        printf("\n4.DISPLAY\n");\
        printf("Enter your choice:");
        scanf("%d",&choice);
        switch(choice)
        {
            case 1:create();
                    break;
            case 2:insert();
                    break;
            case 3:delete();
                    break;
            case 4:display();
                    break;
            case 5: return;
            default:printf("Invalid choice");                                
        }
    }
    //a Creating of an Array of N integers
void create()
{
    printf("Enter the size of the array elements:");
    scanf("%d",&n);
    printf("Enter the elements of array:");
    for(i=0;i<n;i++)
    scanf("%d",&a[i]);
}
//b. Inserting an element to the array 
void insert()
{
    printf("Enter the position for the new element");
    scanf("%d",&pos);
    if(pos>=n=1||pos<0)
    {
        printf("Insertion is not possible");
    }
    else
    {
        printf("Enter the eleme3nt to be inserted:");
        scanf("%d",elem);
        for(i=n-1;i>=pos;i--)
        a[i+1]=elem;
        n++
    }
    //c.Deleting an element from the array
    void delete()
    {
     printf("enetr the position of the element to be deleted");
     scanf("%d",&pos);
     if(pos>=n+1||pos<0)
     {
        printf("Deletion is not possible");
     }
     else
     {
      printf("the deleted element is %d",a[pos]);
      for(i=0;i<n-1;i++)
      a[i]=a[i+1]
      n--;
     }
    }
    //display of an array
    void dispaly()
    {
        printf("the array elemts are ");
        for(i=0;i<n;i++)
        printf("a[%d]=%d",i,a[i]);
    }
}
}
