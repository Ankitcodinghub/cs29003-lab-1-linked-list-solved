# cs29003-lab-1-linked-list-solved
**TO GET THIS SOLUTION VISIT:** [CS29003 Lab 1-Linked List Solved](https://www.ankitcodinghub.com/product/cs29003-lab-1-linked-list-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92893&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS29003 Lab 1-Linked List Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Doubly linked list with one pointer per node!

Recall that, in a singly linked list, every node of a linked list stores some data value and a pointer to the next node in the list; the value of the next pointer of the last node is set to NULL. The idea of singly linked list has been extended to doubly linked list as follows. In a doubly linked list, we store a pointer to the next node and another pointer to its previous node. Please refer to Figure 1 for a pictorial overview.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
prev = …

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
next = NULL

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
prev = NULL

</div>
</div>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
<div class="layoutArea">
<div class="column">
next = 300

</div>
</div>
<div class="layoutArea">
<div class="column">
prev = 100

</div>
</div>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
<div class="layoutArea">
<div class="column">
next = …

</div>
</div>
<div class="layoutArea">
<div class="column">
•••

</div>
</div>
<div class="layoutArea">
<div class="column">
100 300

</div>
<div class="column">
800

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Usual structure of a doubly linked list with two pointers per node.

Let us tweak this basic structure of a doubly linked list as follows. Instead of storing two pointers per node, let us store only XOR of these two pointers in every node thereby saving (in every node) the space required to store one pointer. Please refer to Figure 2 for a pictorial overview.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
(Address of previous node) XOR NULL

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
data

</div>
</div>
<div class="layoutArea">
<div class="column">
NULL XOR 300 (Address of next node)

</div>
</div>
<div class="layoutArea">
<div class="column">
100

(Address of previous node) XOR (Address of next node)

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
•••

</div>
</div>
<div class="layoutArea">
<div class="column">
100 300

</div>
<div class="column">
800

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: Modified structure of a doubly linked list with one pointer per node.

The XOR function is defined in the following manner. Let X = (x1, x2, . . . , xn) and Y = (y1,y2,…,yn) be two Boolean strings of length n bits each. Then XXORY = (x1 XORy1,x2 XORy2,…,xn XORyn) where 0XOR0 = 0,1XOR1 = 0,0XOR1 = 1,1XOR0 = 1. One can easily verify the following properties of the XOR function.

◃ XXORY=YXORX

◃ (XXORY)XORZ=XXOR(YXORZ) ◃ X XOR X = 0 ̄

Convince yourself that all the usual operations on a doubly linked list can still be carried out correctly in our modified representation. In this exercise, you first take the length n of a doubly linked list from

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
the user. Then create a doubly linked list of length n with integers values as given by the user. Needless to say that you should only store the XOR of the addresses of the previous and the next node in every node as discussed above. Thus, the following data structure can be used:

<pre>struct node{
int data; // stores the value in the node.
struct node *add; // stores the XOR value of the next and prev pointer.
};
</pre>
Also, here is how you can perform XOR operation on the addresses.

<pre>struct node *add, *prev *next;
//Assume that add should store XOR of prev and next
add = (unsigned long long)prev^(unsigned long long)next;
</pre>
Note that for every doubly linked list, you maintain a head and a tail pointer pointing respectively to the first and the last node of the list. In this doubly linked list, you perform the following operations:

1. Traverse the doubly linked list both from the front to the end and from the end to the front and print data values in that order. The prototype of your functions should be as follows.

void traverse from front to end(struct node *head); void traverse from end to front(struct node *tail);

2. Reverse your doubly linked list. Once the doubly linked list is created in the start, you SHOULD NOT create any new node and change data field of any node. The prototype of your function should be as follows.

void reverse(struct node **head, struct node **tail);

Observe that you need to pass double pointers here since the doubly linked list is going to change unlike traversal functions. Use function defined in part 1 to traverse the new list from front to end.

3. Transform the doubly linked list into having alternate values from the beginning and end. After transformations, the first element of the new linked list should be the first element of the original linked list, the second element of the new linked list should be the last element of the original linked list, the third element of the new linked list should be the second element of the original list, the fourth element of the new linked list should be the 2nd last element of the original linked list, and so on. Once the doubly linked list is created in the start, you SHOULD NOT create any new node and change data field of any node. The prototype of your function should be as follows:

void alternate(struct node **head, struct node **tail);

Here also you need to pass double pointers since the linked list is going to change. Note that this operation needs to be done on the reversed linked list formed in the previous step. Use function defined in part 1 to traverse this list from front to end.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Sample Output

</div>
</div>
<div class="layoutArea">
<div class="column">
n = 10

Enter the 10 integers between -100 to 100: 3, 10, −12, 34, −10, −50, 25, 1, −18, −71

Doubly linked list traversed from front to end: 3, 10, −12, 34, −10, −50, 25, 1, −18, −71 Doublylinkedlisttraversedfromendtofront: −71,−18,1,25,−50,−10,34,−12,10,3 Reverseddoublylinkedlisttraversedfromfronttoend: −71,−18,1,25,−50,−10,34,−12,10,3 Alternateddoublylinkedlisttraversedfromfronttoend: −71,3,−18,10,1,−12,25,34,−50,−10

File Naming Convention

Please note that your submissions will not be evaluated unless you follow the below specified file naming convention for the program file. &lt;ROLLNO(IN CAPS)&gt; Assign&lt;Assign No&gt; G&lt;Group No&gt;.c/cpp

Eg: 18CS30004 G03 Assign1.c / 18CS30004 G03 Assign1.cpp

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
