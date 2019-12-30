# Road-To-DP
---------------------
Dynamic programming

DP1
https://www.interviewbit.com/problems/stairs/
https://www.interviewbit.com/problems/length-of-longest-subsequence/
https://www.interviewbit.com/problems/min-jumps-array/
https://www.interviewbit.com/problems/max-product-subarray/
Hw:- https://www.interviewbit.com/problems/longest-increasing-subsequence/
https://www.geeksforgeeks.org/minimum-number-of-squares-whose-sum-equals-to-given-number-n/
``` Longest Balanced Substring

Given a string S made up of multiple brackets of type "<>" , "[]" , "()" and "{}" find the length of the longest substring which forms a balanced string . Conditions for a string to be balanced : 1) Blank string is balanced ( However blank string will not be provided as a test case ). 2) if B is balanced : (B) , [B] , {B} and <B> are also balanced. 3) if B1 and B2 are balanced then B1B2 i.e the string formed by concatenating B1 and B2 is also balanced. Your function will get exactly one argument which would represent the string S. Your function should return an integer corresponding to the answer. Constraints :
0 <= length(S) <= 1000000
Sample Test Case :
Input : <<<<>
Output : 2 

``` https://www.interviewbit.com/problems/coins-in-a-line/
https://www.interviewbit.com/problems/best-time-to-buy-and-sell-stocks-i/  

DP2
https://www.interviewbit.com/problems/min-sum-path-in-matrix/
``` Let's Party

In Danceland, one person can party either alone or can pair up with another person. Can you find in how many ways they can party if there are N people in Danceland? Input Format
Given only argument A of type Integer, number of people in Danceland.
Output Format
Return a single integer N mod 10003, i.e number of ways people of Danceland can party.
Constraints
1 <= N <= 1e5 
Example Input 1: N = 3 Example Output 1: 4 Explanation 1: Let suppose three people are A, B, and C. There are only 4 ways to party as, (A, B, C) All party alone (AB, C) A and B party together and C party alone (AC, B) A and C party together and B party alone (BC, A) B and C party together and A party alone here 4 % 10003 = 4, so answer is 4.
``` https://www.interviewbit.com/problems/ways-to-decode/ https://www.interviewbit.com/problems/longest-arithmetic-progression/ https://www.interviewbit.com/problems/n-digit-numbers-with-digit-sum-s-/ hw:- ``` Maximum Sum

You are given an array A of N integers and three integers X, Y, and Z. You have to find the maximum value of A[i]*X + A[j]*Y + A[k]*Z, where 1 <= i <= j <= k <= N. Input Format
1st argument is an array A
2nd argument is an integer X
3rd argument is an integer Y
4th argument is an integer Z
Output Format
Return an Integer S, i.e maximum value of (A[i]*X + A[j]*Y + A[k]*Z), where  1 <= i <= j <= k <= N.
Constraints
1 <= N <= 1e5
-1e4 <= A[i], X, Y, Z <= 1e4
For Example
Input:
    A = [1, 5, -3, 4, -2]
    X = 2
    Y = 1
    Z = -1
Output:
    18

Explanation:
    if you choose i = 2, j = 2, and k = 3 then we will get
    A[2]*X + A[2]*Y + A[3]*Z = 5*2 + 5*1 + (-3)*(-1) = 10 + 5 + 3 = 18

 ``` https://www.interviewbit.com/problems/grid-unique-paths/ https://www.interviewbit.com/problems/best-time-to-buy-and-sell-stocks-ii/ https://www.interviewbit.com/problems/intersecting-chords-in-a-circle/ https://www.interviewbit.com/problems/coin-sum-infinite/   dp3:-
https://www.interviewbit.com/problems/string-count/ https://www.interviewbit.com/problems/longest-pallindromic-subsequence/ https://www.interviewbit.com/problems/longest-common-subsequence/ https://www.interviewbit.com/problems/longest-palindromic-substring/ hw:- https://www.interviewbit.com/problems/rod-cutting/ ``` Odd Palindrome

A palindrome string is a string which reads the same forward and backward. If a palindrome string is of odd length l, then (l+1)/2th character (1 index based) is said to be the centre of the palindrome. You are given a string A. Return an array X of integers where X[i] = (number of odd length palindrome subsequence of A with A[i] as the centre) modulo 1000000007. A subsequence of A is a string which can be derived from A by deleting some of its character. Constraints:
1 <= length(A) <= 1000
Every character of A will be a lowercase English letter 'a' - 'z'.
Example :
A : xyzx
Returns X as [1, 2, 2, 1]
``` https://www.interviewbit.com/problems/flip-array/ 
Dp4:- https://www.interviewbit.com/problems/edit-distance/ https://www.interviewbit.com/problems/regular-expression-match/ https://www.interviewbit.com/problems/regular-expression-ii/ https://www.interviewbit.com/problems/interleaving-strings/ hw
https://www.interviewbit.com/problems/unique-binary-search-trees-ii/ https://www.interviewbit.com/problems/tushars-birthday-party/ https://www.interviewbit.com/problems/distinct-subsequences/ 

 dp5- https://www.interviewbit.com/problems/palindrome-partitioning-ii/ https://www.interviewbit.com/problems/word-break/ https://www.interviewbit.com/problems/box-stacking-problem/ https://www.interviewbit.com/problems/matrix-chain-multiplication/ hw:- https://www.interviewbit.com/problems/word-break-ii/
https://www.interviewbit.com/problems/russian-doll-envelopes/ https://www.interviewbit.com/problems/length-of-longest-fibonacci-subsequence/ https://www.interviewbit.com/problems/burst-balloons/   DP6 https://leetcode.com/problems/frog-jump/ https://www.interviewbit.com/problems/arithmetic-subsequences/ https://www.interviewbit.com/problems/rectangle-sum/ hw:- ``` Shortest common supersequence

Given two strings A and B, find the shortest string that has both A and B as subsequences.
If multiple answers exist, you may return any of them. Note: A string S is a subsequence of string T if deleting some number of characters from T (possibly 0, and the characters are chosen anywhere from T) results in the string S. Input Format:
First line contains a single integer T denoting the number of test cases.
T lines follow each containing two space separated strings A B
Output Format:
Print T lines each containing a single string.
Note: The string should only contain lower case english alphabets.
Constraints:
1 ≤ T ≤ 10000
1 ≤ |A|,|B| ≤ 1000
sum of |A| * |B| over all test cases does not exceed 10^7
For Example:
Input 1:
    2
    abcd bcde
    xyz abc
Output 1:
    abcde
    axbyzc
Explanation:
    string abcde has both abcd and bcde as subsequence and also has minimum length. For second test case you can also print abcxyz or any other string that follow all condition.

``` https://www.interviewbit.com/problems/distinct-subsequences/


dp-rem*
https://www.interviewbit.com/problems/distinct-subsequences/
https://www.interviewbit.com/problems/min-sum-path-in-matrix/
https://www.interviewbit.com/problems/longest-common-subsequence/
https://www.interviewbit.com/problems/longest-pallindromic-subsequence/
https://www.interviewbit.com/problems/string-count/
Scooby doo likes beautiful strings. Scooby doo calls a string 'S' beautiful if there exists a String 'T' such that S=T+T, where '+' represents the concatenation of the two strings. "aabaab","aa","" are some examples of beautiful strings. Now scooby gives a string s to Shaggy and and asks him to find out the longest beautiful string that can be obtained from s by erasing some of its characters. (Possibly none or in the worst case erasing all the characters). In other words scooby wants the longest beautiful string that occurs in s as a subsequence. Shaggy is a noob with strings and thus needs your help. Help Shaggy by returning the length of the longest possible beautiful string that can be obtained from given string s. Constraints: Number of testcases 1<=T<=150 Length of String 1<=s<=100 Sample Input: aabbab Sample Output: 4 Explanation: abab is the subsequence that is a beautiful string and has length 4. Therefore the answer is 4. Also it can be seen that there is no beautiful string with length greater than 4.
---------------------
curated list of resources and links to learn Dynamic Programming Concepts

Codechef:-
1) https://www.codechef.com/problems/CHRL2
2) https://www.codechef.com/problems/CHRL4

Codeforces:-

1) http://codeforces.com/contest/598/problem/E
2) http://codeforces.com/contest/600/problem/C
3) http://codeforces.com/contest/612/problem/F
4) http://codeforces.com/contest/628/problem/D
5) http://codeforces.com/contest/678/problem/E
6) http://codeforces.com/contest/691/problem/F
7) http://codeforces.com/contest/710/problem/E
8) http://codeforces.com/contest/762/problem/D

