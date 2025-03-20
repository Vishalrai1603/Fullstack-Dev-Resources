# 📅 Day 5: Forms & Inputs in HTML

## 🔹 Introduction to Forms in HTML

Forms are an essential part of web development that allow users to input and submit data to a server for processing. They are widely used in:

- **Login & Signup Forms** – For authentication.
- **Search Bars** – To find information.
- **Contact Forms** – To send messages or inquiries.
- **Feedback & Survey Forms** – To collect user opinions.
- **Payment Forms** – To process transactions.

A form typically consists of **input fields, labels, buttons, and validation rules** to ensure data is collected correctly.

---

## 🔹 Structure of an HTML Form

```html
<form action="submit.php" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br>

    <input type="submit" value="Submit">
</form>
```

### 📌 Explanation:

- `<form>` → Defines the form container.
- `action="submit.php"` → Specifies the **server file** that processes the form data.
- `method="post"` → Determines how data is sent to the server (GET or POST).
- `<label>` → Labels describe form fields and improve accessibility.
- `<input>` → Used to collect different types of user input (text, email, password, etc.).
- `required` → Ensures a field must be filled before submission.

---

## 🔹 Input Fields in HTML Forms

### **1️⃣ Text Input Field**
```html
<label for="username">Username:</label>
<input type="text" id="username" name="username" required>
```

### **2️⃣ Email Input Field**
```html
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
```

### **3️⃣ Password Input Field**
```html
<label for="password">Password:</label>
<input type="password" id="password" name="password" required>
```

### **4️⃣ Number Input Field**
```html
<label for="age">Age:</label>
<input type="number" id="age" name="age" min="18" max="99">
```

### **5️⃣ Radio Buttons (For Selecting One Option)**
```html
<label>Gender:</label>
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>
```

### **6️⃣ Checkboxes (For Selecting Multiple Options)**
```html
<label>Hobbies:</label>
<input type="checkbox" id="reading" name="hobbies" value="reading">
<label for="reading">Reading</label>
<input type="checkbox" id="music" name="hobbies" value="music">
<label for="music">Music</label>
```

### **7️⃣ Drop-down List (Select Menu)**
```html
<label for="city">Choose a city:</label>
<select id="city" name="city">
    <option value="delhi">Delhi</option>
    <option value="mumbai">Mumbai</option>
    <option value="chennai">Chennai</option>
</select>
```

### **8️⃣ Textarea (Multi-line Input Field)**
```html
<label for="comments">Comments:</label><br>
<textarea id="comments" name="comments" rows="4" cols="50"></textarea>
```

---

## 🔹 Form Validation in HTML

### **1️⃣ Required Fields**
```html
<input type="text" name="username" required>
```

### **2️⃣ Min and Max for Numbers**
```html
<input type="number" name="age" min="18" max="60">
```

### **3️⃣ Maximum Length for Text Input**
```html
<input type="text" name="username" maxlength="10">
```

### **4️⃣ Pattern Matching with Regular Expressions (RegEx)**
```html
<input type="email" name="email" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$">
```

### **5️⃣ Validating URLs**
```html
<input type="url" name="website">
```

### **6️⃣ Date Input Validation**
```html
<input type="date" name="dob" min="2000-01-01">
```

### **7️⃣ Disabling Auto-complete for Sensitive Fields**
```html
<input type="password" name="password" autocomplete="off">
```

---

## 🔹 Task: Create a Registration Form with Validation

### 🎯 Features:

- Name (Required)
- Email (Required, Valid Format)
- Gender (Radio Buttons)
- Hobbies (Checkboxes)
- Date of Birth (Required)
- Submit Button



