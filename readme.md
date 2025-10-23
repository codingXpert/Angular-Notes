# 🌟 INTERPOLATION in Angular

**Interpolation** in **Angular** is a **one-way data binding** technique that allows you to display dynamic data from your component class directly within your HTML templates.  
It provides an expressive and intuitive way to embed component data or expressions using double curly braces `{{ }}`, which Angular evaluates and renders as text in the view.

---

## 🧩 What is Interpolation?

Interpolation acts as a bridge between the **component logic (TypeScript)** and the **template (HTML)**.  
It helps render values dynamically, making your UI reflect the current state of your component data.

**One-Way Binding**
- 

- Data flows from the component to the view.

- When component data changes, the template updates automatically.

- However, changes in the view do not directly affect the component’s data through interpolation.

**Template Expressions**
- 
- Component properties

- Method calls

- Simple arithmetic operations

- String literals with JavaScript methods applied to them

**Example**
- 
```html
<p>{{ user.firstName + ' ' + user.lastName }}</p>
<p>{{ getGreetingMessage() }}</p>
<p>{{ price * quantity }}</p>
```



<img width="1122" height="682" alt="Image" src="https://github.com/user-attachments/assets/f6bcb48f-3930-47b4-ae0d-2b7240d00977" />
---

## ⚙️ Key Aspects of Angular Interpolation

### 🔹 **Syntax**
Interpolation uses the **“mustache” syntax**, where expressions are enclosed in double curly braces:

```html
<p>{{ expression }}</p>
```
