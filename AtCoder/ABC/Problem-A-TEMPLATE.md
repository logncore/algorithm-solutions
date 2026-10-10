# A - Welcome to AtCoder

**Problem:** https://atcoder.jp/contests/practice/tasks/practice_1#Python_en
**Language:** Python  
**Status:** Solved

## My understanding
there will be 4 inputs. 3 integers which are a b c and 1 str which is s. a b c are the numbers between 1 and 1000. s is word that has number of letters between 1 and 100.

## My approach
Explain your idea step by step. Why does it work?

## My solution

a = int(input())
b , c= map(int, input().split())
s = str(input())
sum = a + b + c

print(sum, s)


