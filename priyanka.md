# Problem
Alice jogs everyday to keep herself fit and active. She noticed that she burns XX calories when jogging the first kilometer, and for K \gt 1K>1, jogging the K^{th}
kilometer burns calories equivalent to the total number of calories burned while jogging the first K-1K−1 kilometers.

What is the total number of calories that Alice burns after jogging for NN kilometers? The answer can be very large, so report it modulo 10^9 + 7= (1000000007).
<pre>
Input Format:
The first line of input will contain an integer T — the number of test cases. The description of TT test cases follows.
The first and only line of each test case contains two space-separated integers N and X, as described in the problem statement.

Output Format
For each test case, output on a new line the total number of calories that Alice burns after jogging for N kilometers,modulo 10^9+7

Constraints
1 1≤T≤10^5
1 1≤N≤10^6
1 1≤X≤100
</pre>
<pre>
Sample 1:
Input :
3
1 2
2 1
12548 1

Output :
2
2
588809226
</pre>

Explanation:<br>
Test case 1: Alice only jogs one kilometer, which burns 22 calories since X = 2X=2.<br>
Test case 2: Alice jogs two kilometers. The first burns X = 1X=1 calorie, and the second also burns 11 calorie since the total amount burnt before this is 11 calorie.<br>
So, the total is 1 + 1 = 2 calories burned.
