# Algebra

## 📘 Key Concepts

---

### ✅ Identities and Formulas

- **(a + b)² = a² + 2ab + b²**
- **(a - b)² = a² - 2ab + b²**
- **a² - b² = (a + b)(a - b)**
- **(a + b)³ = a³ + 3a²b + 3ab² + b³**
- **(a - b)³ = a³ - 3a²b + 3ab² - b³**
- **a³ + b³ = (a + b)(a² - ab + b²)**
- **a³ - b³ = (a - b)(a² + ab + b²)**

---

### 🔢 Example: Use of Identities

**Example 1:**
```
(867 + 289)(867 - 289) = 867² - 289² = a² - b² form
```

**Example 2:**
```
4x² + 9y² + 12xy = (2x + 3y)²
```

**Example 3:**
```
4x² + 9y² - 12xy = (2x - 3y)²
```

---

### ✅ Quadratic Equations

A **quadratic equation** is a polynomial equation of degree 2:

```
ax² + bx + c = 0
```

Where:
- `a ≠ 0`
- `a, b, c` are real or complex coefficients

---

## 📐 Standard Formula for Roots

```
x = [-b ± √(b² - 4ac)] / 2a
```

Where:
- Discriminant `D = b² - 4ac` determines the nature of roots.

---

## 🔍 Nature of Roots Based on Discriminant

- **If D > 0 and perfect square** → Real and Rational Roots
- **If D > 0 but not perfect square** → Real and Irrational Roots
- **If D = 0** → Real and Equal Roots
- **If D < 0** → Complex or Imaginary Roots

---

### ✏️ Example 1: Roots are real and equal

Given:
```
4x² + 6mx + 9 = 0
```

Find `m` such that roots are equal.

Set:
```
D = b² - 4ac = 0
→ (6m)² - 4×4×9 = 0
→ 36m² = 144 → m² = 4 → m = ±2
```

---

### ✏️ Example 2: Roots are real and irrational

Given:
```
x² + 12x + 35 = 0
```

Check `D`:
```
D = 12² - 4×1×35 = 144 - 140 = 4 → perfect square
→ Roots are real and rational
```

---

### ✏️ Example 3: Roots are imaginary

Given:
```
√2 x² - 3x + 3√2 = 0
```

Check `D`:
```
D = (-3)² - 4×√2×3√2 = 9 - 24 = -15 < 0
→ Roots are imaginary
```

---

## 🧮 Maximum or Minimum Value of Quadratic

Quadratic: `f(x) = ax² + bx + c`

- **If a > 0** → Minimum value at x = -b/2a
- **If a < 0** → Maximum value at x = -b/2a

Value at that point:
```
f(x) = (4ac - b²) / 4a
```

---

### ✏️ Example 4: Find max/min value

```
f(x) = 2x² + 3x + 4
a = 2 > 0 → Minimum at x = -3/(2×2) = -3/4
```

---

## 🎯 Forming Quadratic Equation from Roots

If `α` and `β` are roots, the equation is:

```
x² - (α + β)x + (αβ) = 0
```

---

### ✏️ Example 5: Roots are 2 + √3 and 2 - √3

- Sum = 4, Product = (2 + √3)(2 - √3) = 4 - 3 = 1  
- Equation:  
  ```
  x² - 4x + 1 = 0
  ```

---

## 🔗 Conditions for Common Roots

Given two equations:

```
a₁x² + b₁x + c₁ = 0  
a₂x² + b₂x + c₂ = 0
```

- **Both roots common**: coefficients are proportional  
  ```
  a₁/a₂ = b₁/b₂ = c₁/c₂
  ```

- **One root common**:

  ```
  (b₁c₂ - b₂c₁)² = (a₁b₂ - a₂b₁)(c₁a₂ - c₂a₁)
  ```

---

### ✅ Cubic Equations

If a, b, c are roots of:
```
ax³ + bx² + cx + d = 0
```

Then:
- Sum of roots = -b/a
- Sum of product of roots (two at a time) = c/a
- Product of roots = -d/a

---

## 📙 Special Patterns and Tricks

### Symmetricity
If an expression is symmetric in variables (e.g., same power terms repeating), you can assume:

```
a = b = c = value
```

Plug in and solve easily.

---

### Factorization Tips

Use:
- (x + a)(x + b) = x² + (a + b)x + ab
- (x - a)(x - b) = x² - (a + b)x + ab

---

### Rationalization

If denominator is irrational like:
```
1 / (√a + √b)
```
Multiply numerator and denominator by the conjugate:
```
√a - √b
```

---

## 🧠 Crow Techniques (Shortcut Tricks)

### ✅ 1. Common Patterns

- If **x + 1/x = a**, then:
  - x² + 1/x² = a² - 2
  - x³ + 1/x³ = a³ - 3a

- If **x - 1/x = a**, then:
  - x² + 1/x² = a² + 2
  - x³ - 1/x³ = a³ - 3a

---

### ✅ 2. Shortcuts for Cubes

If:
```
a + b + c = 0
```
Then:
```
a³ + b³ + c³ = 3abc
```

---

### ✅ 3. Special Values

If:
```
x + 1/x = ±√3 ⇒ x³ + 1/x³ = 0
x + 1/x = ±2 ⇒ x² + 1/x² = 2
```

---

### ✅ 4. Product = 1 Shortcut

If:
```
x × y = 1
```
Then:
```
1 / (1 + x)(1 + y) = 1 / (2 + x + y)
```

---

### ✅ 5. Greatest/Smallest Value Logic

- If product is same, the **max value** comes from **max sum**.
- If sum is same, the **min value** comes from **max product**.

---

### ✅ 6. For A.P. Expressions

If a, b, c in A.P.:
```
a + b + c = 3b  
a² + b² + c² - ab - bc - ca = 0  
a³ + b³ + c³ - 3abc = (a + b + c)(a² + b² + c² - ab - bc - ca)
```

---

### ✅ 7. Use of Identities in Reverse

Sometimes problems are given as:
```
x² + y² = 10, xy = 6  
Then x⁴ + y⁴ = ?
```
Use:
```
(x² + y²)² = x⁴ + y⁴ + 2x²y²  
⇒ 100 = x⁴ + y⁴ + 72  
⇒ x⁴ + y⁴ = 28
```

---

## 📎 Summary

- Master basic identities and reverse them
- Look for symmetry or known patterns
- Use smart substitution where values repeat
- Use discriminant D = b² - 4ac to quickly assess root nature
- **Crow shortcuts** are extremely useful for rapid MCQ solving

