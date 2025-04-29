# Compound Interest

## What is Compound Interest?

- **Compound Interest (CI)** is the interest calculated on the initial principal and also on the accumulated interest from previous periods.
- Unlike Simple Interest, CI grows faster because it earns "interest on interest."

---

## Basic Formula

When interest is compounded annually:

```
A = P × (1 + r/100)^t
CI = A - P
```
Where:
- **P** = Principal
- **r** = Rate of Interest per annum
- **t** = Time in years
- **A** = Final Amount
- **CI** = Compound Interest

---

## If Interest is Compounded Half-Yearly, Quarterly, Monthly

Adjust the formula:

- For **half-yearly**:
  ```
  Rate = r/2
  Time = 2t
  ```

- For **quarterly**:
  ```
  Rate = r/4
  Time = 4t
  ```

- For **monthly**:
  ```
  Rate = r/12
  Time = 12t
  ```

**Example:**
- Principal = ₹5000, Rate = 8% compounded half-yearly for 2 years.

  ```
  New rate = 8/2 = 4%
  New time = 2 × 2 = 4 periods
  A = 5000 × (1 + 4/100)^4
  A = ₹5,000 × (1.04)^4 ≈ ₹5,416.32
  CI = A - P = ₹416.32
  ```

---

## Methods to Solve Compound Interest

### 1. Basic Formula Method

Use the compound interest formula directly.

---

### 2. Tree Method

- Break the interest into year-wise layers.
- First year interest calculated on principal.
- Second-year interest calculated on principal + first year interest, and so on.

---

### 3. Successive Percentage Method

When applicable:

```
Net % increase = a + b + (ab/100)
```
where **a** and **b** are the percentage increases each year.

**Example:**
- 20% for 2 years:

  ```
  Net % = 20 + 20 + (20×20)/100 = 44%
  ```

Thus, effective increase = 44%.

---

### 4. Ratio Method

Useful when percentages are clean fractions.

**Example:**
- 20% means 5/4.

Thus for two years:
- (5/4)² = 25/16 ratio.

This helps to quickly calculate without full multiplication.

---

## Important Observations

- **Amount and CI** for successive years form a **geometric progression**.
- **Difference between CI and SI** becomes noticeable for longer periods and higher rates.
- **Shortcuts** available for specific rates (5%, 10%, 20%, etc.) using successive % tables.

---

## Examples

**Example 1:**
- Find CI on ₹2500 at 20% p.a. for 2 years.

Using successive percentage:

```
Net % = 20 + 20 + (20×20)/100 = 44%
CI = (44/100) × 2500 = ₹1100
Amount = 2500 + 1100 = ₹3600
```

---

**Example 2:**
- Find CI when principal = ₹10000, rate = 10% p.a., for 3 years.

Using basic formula:

```
A = 10000 × (1 + 10/100)^3
A = 10000 × (1.1)^3 = 10000 × 1.331 = ₹13,310
CI = 13310 - 10000 = ₹3310
```

---

## Special Cases

### 1. Finding Time

If Amount and Principal are given:

```
(Amount / Principal) = (1 + r/100)^t
```
Take log or simple trial and error for small powers.

---

### 2. Finding Rate

If Principal, Amount, and Time are known:

Rearrange:
```
(Amount / Principal) = (1 + r/100)^t
```
Solve for **r**.

---

### 3. Difference Between CI and SI

- For **2 years**:

  ```
  Difference = P × (r/100)²
  ```

- For **3 years**:

  Use successive formula or expand tree.

---

# Crow Techniques (Shortcut Tricks)

✅ **For 2 Years - Quick Shortcut:**

If Rate = R%:

```
Net Increase % = 2R + (R²/100)
```

✅ **Successive Percentage Rule:**

```
Effective Increase % = a + b + (ab/100)
```

✅ **Tree Method Shortcut:**

- 1st Year Interest: `P × r/100`
- 2nd Year Interest: `1st year Interest × r/100`

Add them up for quick CI.

✅ **Ratio Method:**

When Rate % is easy fraction:
- (Rate as fraction)² gives Amount to Principal ratio.

✅ **Memory Table for Fast Calculation:**

| Rate (%) | Net % Increase after 2 years |
|:--------:|:----------------------------:|
| 5%       | 10.25%                       |
| 10%      | 21%                          |
| 15%      | 32.25%                       |
| 20%      | 44%                          |
| 25%      | 56.25%                       |

---

# Summary

- **Use Basic Formula** when exact numbers.
- **Use Successive Percentage** for common percentages.
- **Use Tree Method** when layered interest questions.
- **Crow Techniques** for fastest solving in exams.
