# Основы JavaScript: Циклы, Условия и Функции

JavaScript — это мощный язык программирования, широко используемый для веб-разработки. Этот файл расскажет вам о базовых элементах: **циклах**, **условиях** и **функциях**.

---

## **Циклы**
Циклы используются для повторения блока кода несколько раз. Основные виды циклов:

### **1. Цикл `for`**
Используется, когда количество итераций известно заранее.
```javascript
for (let i = 0; i < 5; i++) {
    console.log(i); // Выводит числа от 0 до 4
}
```

### **2. Цикл `while`**
Работает, пока условие истинно.
```javascript
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

### **3. Цикл `do...while`**
Сначала выполняет блок кода, а затем проверяет условие.
```javascript
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);
```



## **Условия**
Условия управляют выполнением кода в зависимости от истинности выражения.

### **1. `if...else`**
```javascript
const age = 18;
if (age >= 18) {
    console.log("Доступ разрешен");
} else {
    console.log("Доступ запрещен");
}
```

### **2. `else if`**
```javascript
const score = 85;
if (score >= 90) {
    console.log("Отлично");
} else if (score >= 75) {
    console.log("Хорошо");
} else {
    console.log("Улучшайте результаты");
}
```

### **3. Тернарный оператор**
Короткая запись условий.
```javascript
const isLoggedIn = true;
const message = isLoggedIn ? "Добро пожаловать" : "Пожалуйста, войдите";
console.log(message);
```

---

## **Функции**
Функции — это блоки кода, которые выполняются при вызове. Они помогают организовать и переиспользовать код.

### **1. Function Declaration**
```javascript
function greet(name) {
    return `Привет, ${name}!`;
}

console.log(greet("Иван")); // "Привет, Иван!"
```

### **2. Function Anonymous **
```javascript
const sum = function (a, b) {
    return a + b;
};

console.log(sum(3, 4)); // 7
```

### **3. Arrow Function**
Короткий синтаксис для объявления функций.
```javascript
const multiply = (a, b) => a * b;
console.log(multiply(2, 3)); // 6
```

