# palindrome-check
# 🔁 Palindrome Number Checker in Java

This is a simple Java program that checks whether a given number is a **palindrome**

## ✅ What is a Palindrome Number?

A **palindrome** number is a number that remains the same when its digits are reversed.

**Examples:**
- `121` → Palindrome ✅  
- `1331` → Palindrome ✅  
- `123` → Not a palindrome ❌  
- `45654` → Palindrome ✅

---

## 💡 Program Logic

The program works by **reversing the number** and then comparing it with the **original number**.

### Step-by-step Logic:

1. **Input a number** from the user.
2. **Store the original number** in a separate variable (`originalNumber`).
3. **Initialize** a variable `reversed = 0`.
4. **Loop** through the number using `while (number != 0)`:
   - Get the **last digit** using `number % 10`.
   - Add the digit to the **reversed number** by multiplying the current `reversed` by 10 and adding the digit.
   - Remove the last digit from the number using `number / 10`.
5. After the loop, **compare** the original number and the reversed number:
   - If they are **equal**, it's a palindrome.
   - Otherwise, it's **not a palindrome**.

---

## 🛠️ How to Run

1. Save the Java code in a file named `PalindromeCheck.java`.
2. Open your terminal or command prompt.
3. Compile the program:
   javac PalindromeCheck.java
Run the compiled program:

java PalindromeCheck
🧪 Sample Output
Enter a number: 121
121 is a palindrome.

Enter a number: 456
456 is not a palindrome.
