# com2067-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [COM2067 Lab 5 Solved](https://www.ankitcodinghub.com/product/com2067-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99957&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM2067 Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Customers who are waiting to make transactions in a bank located in a residential area with a low population density are in a “queue”. The employees who perform the operations are located in a “stack”. The Bank is considering using employees as a “stack” to run some of its employees in transactions of its customers to the maximum, and some of its employees who are unable to provide service to its customers due to its “stack” structure in some other office work. In this way, the employee working at the desk will be less distracted and she/he will complete the work efficiently. Suppose you have 6 employees (the number of employees is fixed in this study and it is 6) (employee ids are given 1 to 6, employee 6 is at the top of stack) in the bank.

Input Output

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
122 1 2 128 1 1 113 1 2 118 2 3 119 2 5 115 2 9 127 3 1 156 3 4 112 3 5 121 3 7 -1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
122 6 1 3 0 128 5 1 2 0 113 4 1 3 0 118 5 2 5 0 119 3 2 7 0 115 2 2 11 0 127 6 3 4 0 156 4 3 7 0 112 1 3 8 0 121 6 4 11 1

6 10 54 46 35 29 15

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
In the given input, the first customer with the account number 122 comes to the bank in the 1st minute and has 2 minutes processing. (You can think of “comes in the first minute” as coming at the beginning of the first minute). Write a C program that process the transactions (given in the text file), that took place from the beginning of the 1st minute until the time when no customers are left in the bank. The output will consist of customer number, employee number, time the transaction started, time the transaction finished, customer waiting time in queue. Additionally each employee’s total serving time will be printed.

If you examine the output, you can see that the customer with account number 122 arrives in the 1st minute, the transaction is completed at the beginning of 3rd minute (because of the 2-minute process) and does not wait at all in the queue. Since this is the first customer to arrive, the bank employee at the top of the stack, namely the bank employee with identification number 6, took care of him. The second customer was taken care of the bank employee with identification number 5 (the topmost member of the stack after 6). The bank employee, whose job is finished, settles on the top of the back pile. Write and use all the necessary methods of “Stack” and “Queue” structures in your program. You can implement stacks and queues using either array or link list.

</div>
</div>
</div>
