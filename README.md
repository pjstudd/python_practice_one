# 🧠 PYTHON EXPRESSION HELL  
## User Profile Consistency Checker (NO CONTROL STRUCTURES)

---

## 😈 A Friendly (But Diabolical) Introduction

Hello my dear students 👁️👁️  

Today, you will suffer… *academically*.  
This exercise was carefully designed to **remove your safety nets**, strip away your beloved `if` statements, and force you to confront Python **as it truly is**:  
a language of **expressions, operators, and silent judgment**.

There will be:
- ❌ No `if`
- ❌ No loops
- ❌ No shortcuts
- ❌ No mercy

Only **pure expressions**, **data types**, and **operators**.  
If your code runs, congratulations.  
If it *looks wrong but works*, congratulations again.  
If you try to sneak in a control structure…  
👀 **I will know.**

Proceed carefully.

---

## 📌 Objective

Analyze and validate a user profile **using only expressions**.  
You must compute several values based on the given data **WITHOUT using control structures**.

---

## 🚫 STRICT RULES (READ THIS OR REGRET IT)

You are **NOT ALLOWED** to use:

- `if`, `else`, `elif`
- `for`, `while`
- `match`
- `try / except`
- list, set, or dict comprehensions
- functions or lambdas

Violating any rule results in **automatic failure**.

---

## ✅ ALLOWED TOPICS ONLY

You may use **ONLY** the following:

### Strings
- Concatenation
- Formatting
- String methods

### Data Types
- `list`
- `set`
- `tuple`
- `dict`

### Operators
- Comparison (`==`, `!=`, `>`, `<`, `>=`, `<=`)
- Logical (`and`, `or`, `not`)
- Identity (`is`, `is not`)
- Membership (`in`, `not in`)

---

## 📥 Given Data

```python
profile = {
    "username": "Pat_Dev",
    "email": "patdev@gmail.com",
    "skills": ["Python", "Laravel", "Flutter", "Python"],
    "roles": ("admin", "editor"),
    "active": True,
    "login_devices": {"laptop", "mobile", "tablet"},
    "metadata": {
        "verified": True,
        "age": 21
    }
}

🧩 TASKS (YES, YOU MUST DO ALL OF THESE)
1️⃣ Username Analysis
Create a string variable named username_report that:
Converts the username to UPPERCASE
Appends the username length using string formatting
📌 Exact format:
USERNAME: PAT_DEV | LENGTH: 7


2️⃣ Skill Uniqueness Check
Create a boolean variable named has_duplicate_skills that:
Is True if the skills list contains duplicate values
Is False otherwise
🚫 No loops
🚫 No conditionals


3️⃣ Role Membership Validation
Create a boolean variable named is_admin that:
Checks whether "admin" exists inside the roles tuple


4️⃣ Device Consistency Check
Create a boolean variable named valid_device_count that:
Is True if the number of login devices is greater than or equal to 2


5️⃣ Email Domain Verification
Create a boolean variable named is_valid_email that checks:
The email contains "@"
The email ends with "gmail.com"
Use string methods and logical operators only.


6️⃣ Profile Integrity Summary
Create a string variable named summary with this exact format:
User Pat_Dev | Admin: True | Verified: True | Devices: 3


Rules:
Use string concatenation or formatting
Pull values directly from the dictionary
No conditionals allowed


7️⃣ Identity Check
Create a boolean variable named is_active_user that:
Uses the identity operator
Checks whether profile["active"] is True
🚫 Do NOT use ==


🧪 Expected Output Types

| Variable Name        | Expected Type |
| -------------------- | ------------- |
| username_report      | `str`         |
| has_duplicate_skills | `bool`        |
| is_admin             | `bool`        |
| valid_device_count   | `bool`        |
| is_valid_email       | `bool`        |
| summary              | `str`         |
| is_active_user       | `bool`        |
