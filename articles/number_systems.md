## Number System

---

## 📘 Types of Numbers

- **Natural Numbers**: Numbers used for counting  
  ➤ Example: 1, 2, 3, 4, …

- **Whole Numbers**: Natural numbers plus zero  
  ➤ Example: 0, 1, 2, 3, …

- **Integers**: Positive and negative whole numbers  
  ➤ Example: -2, -1, 0, 1, 2

- **Rational Numbers**: Numbers that can be written as a fraction  
  ➤ Example: 1/2, -3/4, 0.75

- **Irrational Numbers**: Numbers that cannot be written as fractions  
  ➤ Example: √2, π

- **Real Numbers**: All rational and irrational numbers together

- **Even Numbers**: Divisible by 2  
  ➤ Example: -4, 0, 2, 6

- **Odd Numbers**: Not divisible by 2  
  ➤ Example: -3, 1, 5

- **Prime Numbers**: Only two factors: 1 and itself  
  ➤ Example: 2, 3, 5, 7

- **Composite Numbers**: More than two factors  
  ➤ Example: 4, 6, 9, 12

---

## ➗ Understanding Remainders

When a number is divided and doesn’t divide exactly, the leftover part is the **remainder**.

**Formula:**  
```
Number = Divisor × Quotient + Remainder
```

**Example:**  
If we divide 925 by 38  
→ 38 × 24 = 912  
→ Remainder = 925 - 912 = **13**

---

## 🔄 Additive and Multiplicative Properties of Remainders

- If 361 ÷ 12 gives remainder **1**, and 363 ÷ 12 gives **3**,  
then:  
→ (361 × 363) ÷ 12 will give remainder = **1 × 3 = 3**

---

## 🔁 Successive Division

Divide in reverse to find the original number:

**Example:**  
If remainders are:
- ÷7 → 4  
- ÷4 → 1  
- ÷3 → 2  

Steps:  
→ 4 × 4 + 1 = 17  
→ 17 × 3 + 2 = **53**

So, the number is **53**

---

## 📗 Famous Theorems Made Simple

---

### 1. **Fermat’s Remainder Theorem**

When a number `N` and a **prime divisor** `P` have no common factor (i.e., co-prime),  
Then:
```
N to the power of P gives remainder = N
N to the power of (P - 1) gives remainder = 1
```

**Example:**  
11⁷ ÷ 7  
→ 11 and 7 are co-prime  
→ Remainder = **4** after simplifying using Fermat

---

### 2. **Euler’s Remainder Theorem**

If numbers are co-prime and the divisor is **not a prime**, we use **Euler’s number**.

**Step to find Euler’s Number (ϕ(n))**:  
ϕ(n) = n × (1 - 1/p₁) × (1 - 1/p₂) × …  
Where p₁, p₂ are **prime factors** of n.

**Example:**  
Find remainder of 11⁷ when divided by 7  
- 11 and 7 are co-prime  
- 7 is a prime → So, ϕ(7) = 7 × (1 - 1/7) = 6  
- Now, 11⁷ = 11 × (11⁶), and 11⁶ ÷ 7 gives remainder 1  
→ Final remainder = 11 ÷ 7 = **4**

---

### 3. **Wilson’s Theorem**

If P is a **prime number**, then:
```
(P - 1)! + 1 is exactly divisible by P
```

**Example:**  
(40)! + 1 ÷ 41 → Remainder = **0**

---

## 🔢 Binary and Decimal Conversion

### Decimal to Binary

Steps:  
1. Divide the number by 2.  
2. Record the remainders.  
3. Write the remainders in reverse order.

**Example:**  
127 → (1111111)₂

---

### Binary to Decimal

Steps:  
1. Multiply each bit by 2 raised to its position.  
2. Add all results.

**Example:**  
(11001)₂ = 1×2⁴ + 1×2³ + 0×2² + 0×2¹ + 1×2⁰ = **25**

---

## 🧠 Crow Techniques (Fastest Tricks)

---

### ✅ Crow Trick 1: Remainder from A.P. with Odd Powers

If numbers are in increasing pattern (like 16, 17, 18, 19) and power is odd:
```
Sum of powers is divisible by the sum of numbers
→ Remainder = 0
```

---

### ✅ Crow Trick 2: Multiply Small Remainders

Instead of multiplying big numbers:
- Divide each separately and multiply their remainders.

**Example:**  
361 ÷ 12 → 1  
363 ÷ 12 → 3  
→ Final remainder = 1 × 3 = **3**

---

### ✅ Crow Trick 3: Fix Negative Remainders

If remainder is -1 and divisor is 11:  
→ Final remainder = 11 - 1 = **10**

---

### ✅ Crow Trick 4: Use Fermat or Euler for Big Powers

- Use **Fermat** if divisor is prime  
- Use **Euler** if numbers are co-prime but divisor is not prime

---

### ✅ Crow Trick 5: Remainder from Polynomial Division

To find the remainder of f(x) ÷ (x - a):  
→ Just plug in x = a in f(x)

---

### ✅ Crow Trick 6: Convert Decimal ↔ Binary Easily

- Divide by 2 and reverse for Decimal → Binary  
- Multiply by 2 powers for Binary → Decimal

---

## 📌 Summary Table

| Concept                          | Shortcut / Rule                                 |
|----------------------------------|--------------------------------------------------|
| Division Formula                 | Number = Divisor × Quotient + Remainder         |
| Fermat’s Theorem                 | Use when divisor is prime and co-prime to base  |
| Euler’s Theorem                  | ϕ(n) = n × (1 - 1/p₁) × (1 - 1/p₂) × …           |
| Wilson’s Theorem                | (P - 1)! + 1 is divisible by P                   |
| Successive Division              | Work backward from last divisor                 |
| Negative Remainder Shortcut      | Add divisor to negative remainder               |
| Decimal ↔ Binary                 | Divide or multiply using powers of 2            |

---

This version of **Number System** includes both core concepts and fastest shortcut tricks to help 6–8 graders master the topic with confidence and
