## LCM and HCF

## What is LCM?

- **LCM (Least Common Multiple)** of two or more numbers is the smallest number that is exactly divisible by each of the numbers.
- LCM is only defined for **positive integers**.

**Example:**
- Multiples of 10: 10, 20, 30, 40, 50, 60...
- Multiples of 15: 15, 30, 45, 60...
- Multiples of 20: 20, 40, 60, 80...
- The smallest common multiple = **60**.

Thus, **LCM(10, 15, 20) = 60**.

---

## Process to Find LCM

### Method-1: Prime Factorization

1. Factorize all numbers into their **prime factors**.
2. Collect **all distinct prime factors**.
3. Take each prime factor with its **highest power**.
4. Multiply them together to get the LCM.

**Example:**
- Find LCM of 18 and 42.

Step 1:  
18 = 2 × 3²  
42 = 2 × 3 × 7

Step 2:  
Distinct primes: 2, 3, 7

Step 3:  
Highest powers: 2¹, 3², 7¹

Thus,  
LCM(18, 42) = 2¹ × 3² × 7¹ = **126**

---

### Method-2: Shortcut by Division

- Write numbers side by side.
- Divide by common prime numbers step-by-step.
- Stop when only 1s remain.
- Multiply all divisors to get the LCM.

---

## What is HCF (or GCD)?

- **HCF (Highest Common Factor)**, also called **GCD (Greatest Common Divisor)**, is the largest number that divides all given numbers exactly.

**Example:**
- HCF of 18 and 42 = **6**

---

## Process to Find HCF

### Method-1: Prime Factorization

1. Factorize each number into **prime factors**.
2. Identify **common prime factors**.
3. Multiply the common prime factors to get the HCF.

**Example:**
- 18 = 2 × 3²  
- 42 = 2 × 3 × 7  

Common factors: 2, 3  
Thus,  
HCF(18, 42) = 2 × 3 = **6**

---

### Method-2: Division Method

1. Divide the larger number by the smaller.
2. Divide the divisor by the remainder.
3. Repeat until remainder is 0.
4. The last non-zero divisor is the HCF.

**Example:**
Find HCF of 18 and 42:

```
42 ÷ 18 = 2 remainder 6  
18 ÷ 6 = 3 remainder 0
```

Thus, HCF(18, 42) = **6**

---

## Important Properties

- **Product of two numbers = HCF × LCM**

**Example:**
- If HCF = 6, LCM = 5040, and one number = 210, then:
  
  Product = HCF × LCM = 6 × 5040 = 30240  
  Other number = 30240 ÷ 210 = **144**

---

## Special Notes

- LCM and HCF are **not defined for negative numbers**.
- If HCF of x and y = H, then:
  - HCF(x, x + y) = H
  - HCF(x, x - y) = H
  - HCF(x + y, x - y) = H

---

## LCM and HCF of Fractions

- **LCM of Fractions** = (LCM of Numerators) ÷ (HCF of Denominators)
- **HCF of Fractions** = (HCF of Numerators) ÷ (LCM of Denominators)

**Example:**
- Find LCM and HCF of 1/2, 2/5, 4/7

Step 1:
- Numerators: 1, 2, 4
- Denominators: 2, 5, 7

Step 2:
- LCM of Numerators = 4
- HCF of Denominators = 1

Thus,
- LCM of fractions = 4 ÷ 1 = **4**

Similarly,
- HCF of Numerators = 1
- LCM of Denominators = 70

Thus,
- HCF of fractions = 1 ÷ 70 = **1/70**

---

## Applications of LCM

- **Finding when events happen together** (bells ringing together, racers meeting at starting point).

**Example:**
- Bells ringing every 12s, 18s, 24s, 36s, 45s.
- Find when they ring together:

LCM(12, 18, 24, 36, 45) = **360 seconds**  
(= 6 minutes)

Thus, they will ring together again after **6 minutes**.

---

## Applications of HCF

- **Finding largest tile size** that can cover a floor without cutting.
- **Finding largest number** dividing given numbers leaving same remainders.

**Example:**
- Dimensions: 360 cm × 540 cm

Find HCF(360, 540):

360 = 2 × 2 × 2 × 3 × 3 × 5  
540 = 2 × 2 × 3 × 3 × 3 × 5

Common factors: 2² × 3² × 5 = 180

Thus, the largest square tile = **180 cm × 180 cm**

---

## Summary

- **LCM**: Smallest common multiple.
- **HCF**: Largest common divisor.
- **Formula**: Product of numbers = HCF × LCM.
- **Use** prime factorization or division methods.
- **Application**: Time, tiling, problems with remainders.

## Crow Techniques – LCM and GCD (HCF)

Use these powerful shortcuts to quickly solve LCM and GCD problems in competitive exams or mental math!

---

## 📌 Quick Definitions

- **LCM (Least Common Multiple)**: Smallest number divisible by all given numbers.
- **GCD or HCF (Greatest Common Divisor)**: Largest number that divides all given numbers exactly.

---

## 🔁 Crow Shortcut Tricks

### ✅ 1. Product Formula

```
LCM × HCF = Product of the Numbers
```

**Use:** If you know any two values (LCM, HCF, one number), you can find the third.

**Example:**
- Numbers = 12 and 18  
  - 12 × 18 = 216  
  - HCF = 6 → LCM = 216 ÷ 6 = 36 ✅

---

### ✅ 2. Prime Factor Trick

**LCM** → Take **highest powers** of all primes.  
**HCF** → Take **lowest powers** of common primes.

**Example:**
- 18 = 2 × 3²  
- 24 = 2³ × 3  
- LCM = 2³ × 3² = **72**  
- HCF = 2 × 3 = **6**

---

### ✅ 3. Two Numbers Trick (using product)

If LCM and HCF of two numbers are known, use:

```
Product = LCM × HCF
```

Solve for missing number if needed.

---

### ✅ 4. LCM from Multiples – Visual Method

Write down 2–3 multiples of each number and pick the **lowest common one**.

**Example:**
- LCM of 8, 12:  
  Multiples of 8: 8, 16, 24, 32...  
  Multiples of 12: 12, 24, 36...  
  LCM = **24**

---

### ✅ 5. HCF from Division – Euclidean Algorithm

For two numbers:

```
HCF(a, b) = HCF(b, a mod b)
```

Repeat until remainder is 0.

**Example:**
- HCF(48, 18)
  ```
  48 ÷ 18 = 2, rem = 12  
  18 ÷ 12 = 1, rem = 6  
  12 ÷ 6 = 2, rem = 0 → HCF = 6
  ```

---

### ✅ 6. Shortcut for LCM of Consecutive Numbers

- LCM of n consecutive numbers is usually divisible by the **largest number**.

**Example:**
- LCM of 4, 5, 6 → Try multiple of 6  
  6 × 5 = 30, 30 is not divisible by 4 → try 60  
  ✅ LCM = **60**

---

### ✅ 7. LCM of Fractions

```
LCM of fractions = (LCM of numerators) ÷ (HCF of denominators)
```

**Example:**
- LCM of 1/2, 2/5, 4/7  
  - LCM(num) = 4, HCF(denom) = 1 → Result = **4**

---

### ✅ 8. HCF of Fractions

```
HCF of fractions = (HCF of numerators) ÷ (LCM of denominators)
```

**Example:**
- HCF of 1/2, 2/5, 4/7  
  - HCF(num) = 1, LCM(denom) = 70 → Result = **1/70**

---

### ✅ 9. Trick to Find Max Size of Tile (HCF)

To cover a floor using square tiles without cutting:

```
HCF(length, breadth) = Largest tile size
```

**Example:**
- 360 cm × 540 cm  
  - HCF = 180 → Use 180 cm tiles

---

### ✅ 10. Coprime Check

If HCF of two numbers = 1 → They are **coprime**.

---

## 💡 Bonus Crow Tips

- For time-related LCM (bells, alarms, rotations):  
  **LCM = Time when they coincide**

- For largest division without remainder:  
  Use **HCF**.

---

## Summary

| Task                        | Trick                              |
|-----------------------------|-------------------------------------|
| LCM of two numbers          | (a × b) ÷ HCF                       |
| HCF of two numbers          | Euclidean Division Method           |
| LCM of fractions            | LCM(num) ÷ HCF(den)                 |
| HCF of fractions            | HCF(num) ÷ LCM(den)                 |
| Max tile/floor question     | Use HCF                             |
| Timing questions (bells)    | Use LCM                             |

---

✅ Use these Crow Techniques for ultra-fast solving in exams, mental math, and interviews.
