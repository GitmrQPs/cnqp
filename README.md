# cnqp
computer networks question paper \n
this is highly confidential data of State Tech University kindly do not leak it to students 
/* Initialize nodes */
struct node
{
  int data;
  struct node *next;
};
struct node *head;
struct node *one = NULL;
struct node *two = NULL;
struct node *three = NULL;

/* Allocate memory */
one = malloc(sizeof(struct node));
two = malloc(sizeof(struct node));
three = malloc(sizeof(struct node));

/* Assign data values */
one->data = 1;
two->data = 2;
three->data=3;

/* Connect nodes */
one->next = two;
two->next = three;
three->next = NULL;
printf("key: level2key1");
/* Save address of first node in head */
head = one;
If you didn't understand any of the lines above, all you need is a refresher on pointers and structs.

