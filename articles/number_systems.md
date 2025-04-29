# Number System

---

## 📘 Types of Numbers

- **Natural Numbers**: Counting numbers starting from 1.  
  Example: 1, 2, 3, 4, …

- **Whole Numbers**: Natural numbers including 0.  
  Example: 0, 1, 2, 3, …

- **Integers**: All positive and negative whole numbers including 0.  
  Example: -2, -1, 0, 1, 2

- **Rational Numbers**: Numbers that can be written as a fraction.  
  Example: 1/2, 3, -5, 0.75

- **Irrational Numbers**: Numbers that cannot be written as a fraction.  
  Example: √2, π

- **Real Numbers**: All rational and irrational numbers combined.

- **Even Numbers**: Numbers divisible by 2.  
  Example: -4, 0, 2, 6

- **Odd Numbers**: Numbers not divisible by 2.  
  Example: -3, 1, 5

- **Prime Numbers**: Numbers with exactly 2 factors: 1 and itself.  
  Example: 2, 3, 5, 7, 11

- **Composite Numbers**: Numbers with more than 2 factors.  
  Example: 4, 6, 8, 9

---

## ➗ What is a Remainder?

When a number does not divide another exactly, the leftover part is the **remainder**.

**Example**:  
If we divide 38 into 925,  
38 × 24 = 912 → Remainder = 925 - 912 = **13**

---

## 🧮 Important Remainder Rules

### 1. When Numbers Are in Arithmetic Pattern
If the numbers (like 8, 9, 10) are in a regular increasing pattern and the power is **odd**, then:

```
(8³ + 9³ + 10³) ÷ (8 + 9 + 10) → Remainder is always 0
```

### 2. Special Case: Power is Odd
If a, b, c are in arithmetic pattern and the power is odd:
```
aⁿ + bⁿ + cⁿ is divisible by a + b + c
```

**Example**:  
16⁷ + 17⁷ + 18⁷ + 19⁷  
Since numbers are in a pattern and 7 is odd,  
→ Remainder = 0

---

## 🔁 Successive Division (Dividing Step-by-Step)

If a number is divided by 3, then the result by 4, and then by 7:

**Example**:  
If remainders are 2 (with 3), 1 (with 4), and 4 (with 7),  
Then the original number is:  
Step 1: 4 × 4 + 1 = 17  
Step 2: 17 × 3 + 2 = **53**

So the number is **53**

---

## 📐 Division Properties

### Additive Property
If we divide 361 and 363 by 12, the remainders are 1 and 3.  
Then:
```
(361 × 363) ÷ 12  
→ 1 × 3 = 3  
So final remainder = 3
```

### Negative Remainder Trick
Sometimes it's easier to work with negative numbers.

**Example**:  
109 ÷ 11  
Instead of subtracting multiple times,  
→ -1 is remainder  
But since remainder must be positive →  
11 - 1 = **10**

---

## 📗 Easy Explanation of Famous Theorems

### 1. **Fermat’s Remainder Rule**
If two numbers have no common factor (other than 1), and one is a prime number like 7, then:
```
When the bigger number is raised to a power and divided by 7, the remainder is 1.
```

**Example**:  
11⁷ divided by 7 → Remainder is **1**

---

### 2. **Euler’s Remainder Rule**
If two numbers are co-prime (no common factor other than 1), and the second number is not prime:
1. First find how many numbers are less than that and co-prime → Call this Euler's number.
2. Then you can use it to find remainder for large powers.

**Example**:  
117 divided by 7 → Euler's number is 6  
11⁶ divided by 7 gives remainder 1  
So 11⁷ → 11 × 1 = **11**  
Now 11 ÷ 7 → Remainder = **4**

---

### 3. **Wilson’s Remainder Rule**
If a number is prime, then:
```
(P - 1)! + 1 is divisible by P
```

**Example**:  
(40)! + 1 divided by 41 → Remainder = **0**

---

## 🔢 Binary and Decimal Conversion

### Decimal to Binary
Divide by 2 and write remainders in reverse order.

**Example**:  
127 → (1111111)₂

### Binary to Decimal
Multiply each binary digit with powers of 2 and add.

**Example**:  
(11001)₂ = 25

---

## 🧠 Crow Techniques (Easiest Tricks)

---

### ✅ Trick 1: Use A + B if Numbers Are in Pattern
If numbers like 16, 17, 18, 19 are in pattern and power is odd:
```
(16⁷ + 17⁷ + 18⁷ + 19⁷) ÷ (16+17+18+19) → Remainder = 0
```

---

### ✅ Trick 2: Use Add and Multiply Remainders
361 → R = 1  
363 → R = 3  
→ 1 × 3 = 3 is final remainder

---

### ✅ Trick 3: Negative Remainder → Make It Positive  
If -1 is remainder in division by 11, then final remainder is 10

---

### ✅ Trick 4: For Big Powers – Use Theorems  
- Use Fermat if dividing by prime number  
- Use Euler if dividing by co-prime but not prime

---

### ✅ Trick 5: Polynomial Division  
If (x + 3) divides a polynomial, remainder is the value when x = -3.

---

### ✅ Trick 6: Successive Division  
Work backward from last divisor.

---

## ✅ Summary Table

| Concept                      | Shortcut / Rule                            |
|-----------------------------|---------------------------------------------|
| Remainder Formula           | Number = Divisor × Quotient + Remainder     |
| Pattern + Odd Power         | Remainder is 0                              |
| Negative Remainder          | Add divisor to make positive                |
| Successive Division         | Work from last remainder backwards          |
| Decimal to Binary           | Divide by 2, reverse remainders             |
| Fermat’s Theorem            | Remainder is 1 when base and divisor are co-prime |
| Euler’s Theorem             | Use special number of values co-prime with divisor |

---

These methods will help students quickly solve remainder and number system questions in a fun and easy way!
