# Pipe & Cistern

---

## 🧊 What is Pipe and Cistern?

This chapter deals with how fast tanks can be filled or emptied using pipes.

- **Filling pipe**: Adds water to the tank
- **Emptying pipe (or leak)**: Removes water from the tank

---

## 🧮 Basic Formulas

### 1. Time to fill when two pipes work together:
If Pipe A fills in `x` hours and Pipe B fills in `y` hours:

```
Total Time = (x × y) / (x + y)
```

---

### 2. Time to empty when both are emptying:
If Pipe A and B both empty a tank in `x` and `y` hours:

```
Time = (x × y) / (x + y)
```

---

### 3. One fills and one empties:
If A fills in `x` hrs and B empties in `y` hrs:

```
Time = (x × y) / (y - x) [If y > x]
```

---

### 4. More than two pipes:
Use **LCM or combined efficiency** for multiple pipes.

**Example:**
A = 6 hrs, B = 8 hrs, C empties in 12 hrs

```
Work done in 1 hr = (1/6 + 1/8 - 1/12)
```

---

## 🔄 Special Case: Replacement due to Leak

If a pipe fills a tank in `x` hrs but due to leak, it takes `x + t` hrs:

Then time taken by **leak** to empty the tank:

```
= (x × (x + t)) / t
```

---

### Example:
A fills in 20 hrs, but due to a leak it takes 24 hrs:

```
Leak time = (20 × 24) / (4) = 120 hrs
```

---

## 🧪 Work Done Logic

- Work = Rate × Time
- Add rate for filling pipes (+)
- Subtract rate for emptying pipes (-)

---

## 📊 Examples

### Example 1:
Pipe A fills in 8 hrs, Pipe B in 12 hrs. C empties in 16 hrs. All opened together.

```
1 hr work = 1/8 + 1/12 - 1/16
→ Take LCM (48): 6 + 4 - 3 = 7
→ Total time = 48 / 7 ≈ 6.86 hrs
```

---

### Example 2:
Pipe A fills in 72 min, B fills in 90 min. Tank filled in 120 min with C (leak) open. Find C’s rate.

```
A = 2.5 units/min, B = 2 units/min  
Together = 4.5 units/min  
In 120 min: 540 units  
C empties = (540 - 360) / 120 = 1.5 units/min
```

---

### Example 3:
Tank fills in 20 hrs, takes 24 hrs due to leakage. Find time taken by leak:

```
= (20 × 24) / 4 = 120 hrs
```

---

### Example 4:
A fills in 15 hrs, B empties in 10 hrs. Both together:

```
Time = (15×10)/(10-15) = -30 hrs → Negative = Emptying
```

---

# 🧠 Crow Techniques (Shortcuts)

---

### ✅ Trick 1: One fills, one empties

Use:

```
Time = (x × y) / (y - x)
```
Always make sure to subtract **filler from emptier** if emptier is faster.

---

### ✅ Trick 2: Pipe + Leak Problem

If leak delays filling:

```
Time taken by leak = (x × (x + t)) / t
```

---

### ✅ Trick 3: Work per minute/hour

Use LCM of hours to convert all to "units per minute"  
Total work = LCM  
Each pipe’s rate = LCM / time

---

### ✅ Trick 4: Closing One Pipe Early

If one pipe is closed early, calculate:
- How much work was done until it closed
- Remaining work done by others

---

### ✅ Trick 5: Use Net Efficiency

Example:
A = 5 units/hr  
B = 4 units/hr  
C = -3 units/hr (emptying)

Net = 6 units/hr  
Work = 216 units  
Time = 216 / 6 = 36 hrs

---

With these formulas and tricks, Pipe & Cistern problems become simple and fun to solve!
