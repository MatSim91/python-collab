### 11 Python Challenges Based on Chapter 1 and 2

These challenges can be solved using **only the material from Chapter 1 and Chapter 2** of *Automate the Boring Stuff with Python* (3rd Edition):  
- Basic data types  
- Expressions & operators  
- Variables  
- `print()`, `input()`, `len()`, `str()`, `int()`, `float()`  
- Boolean operators (`and`, `or`, `not`)  
- Comparison operators  
- Flow control (`if`, `elif`, `else`)  
- Indentation & blocks  

---

## **1. Age Gate**
Ask the user for their age.  
- If age < 13 → `"You are a child."`  
- If 13–17 → `"You are a teenager."`  
- Else → `"You are an adult."`

---

## **2. Password Checker**
Ask for a username and password.  
- If username is `"admin"` **and** password is `"swordfish"` → `"Access granted."`  
- Else → `"Access denied."`

---

## **3. Temperature Advisor**
Ask for the temperature in Celsius.  
- Below 0 → `"It's freezing!"`  
- 0–20 → `"It's cold."`  
- 21–30 → `"Nice weather."`  
- Above 30 → `"It's hot!"`

---

## **4. Name Length Comparator**
Ask for two names.  
Print which one is longer, or `"They are the same length"` if equal.

---

## **5. Case‑Insensitive Country Greeting**
Ask the user for a country name.  
If they type any variation of `"spain"` → `"Hola!"`  
Otherwise → `"Hello!"`

---

## **6. Even or Odd Detector**
Ask the user for a number.  
- If number % 2 == 0 → `"Even"`  
- Else → `"Odd"`

---

## **7. Mini Calculator**
Ask for two numbers and an operator (`+`, `-`, `*`, `/`).  
Use `if/elif/else` to perform the correct operation.  
If operator is invalid → `"Unknown operator"`

---

## **8. Boolean Logic Quiz**
Ask two yes/no questions. Convert `"yes"` → `True`, `"no"` → `False`.  
- Both True → `"You like both!"`  
- At least one True → `"You like at least one!"`  
- Both False → `"You like neither!"`

---

## **9. Multi-Condition Access Check**
Ask the user for their age and whether they have a membership (`yes`/`no`).  
Grant access if:  
- age ≥ 18 **and** they have a membership  
- OR age ≥ 21 (membership not required)  
Otherwise, deny access.

---

## **10. Hard Drive Truth Checker**
Ask for advertised gigabytes (GB).  
If > 0:  
real = advertised * (1_000_000_000 / 1_073_741_824)
Print the real capacity rounded to 2 decimals.  
Else → `"Invalid capacity"`

---

## **11. Tiered Pricing Calculator**
Ask the user for the number of units they want to buy.  
Use this pricing structure:  
- 1–9 units → 10€ each  
- 10–49 units → 8€ each  
- 50+ units → 5€ each  

Calculate and print the total price based on the correct tier.
