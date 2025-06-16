# 🧱 Custom Queue Implementation in C++

This project implements a **template-based queue** (`clsMyQueue`) using a custom **doubly linked list** (`clsDblLinkedList`) in C++. It demonstrates object-oriented programming and reusable data structures in a clean and modular design.

---

## 📦 Features

- `push(item)`: Add item to the back of the queue
- `pop()`: Remove item from the front
- `front()`: Get the front item
- `back()`: Get the last item
- `Print()`: Print all elements
- `Size()`, `IsEmpty()`, `Clear()`: Utility functions
- Bonus features via the underlying linked list:
  - `Reverse()`
  - `InsertAtFront()`, `InsertAtBack()`
  - `InsertAfter(index, value)`
  - `UpdateItem(index, value)`
  - `GetItem(index)`

---

## 🧪 Example Usage

```cpp
#include "clsMyQueue.h"

int main() {
    clsMyQueue<int> q;

    q.push(10);
    q.push(20);
    q.push(30);

    q.Print();           // Output: 10 20 30
    q.pop();
    cout << q.front();   // Output: 20
    cout << q.back();    // Output: 30

    return 0;
}
````

---

## 🔍 Concepts Demonstrated

* Templates and generic programming
* Queue data structure using a doubly linked list
* Clean class abstraction and modularity
* Dynamic memory management in C++

---

## 📜 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and share it.

---

## 👨‍💻 Author

Built with C++ and curiosity by [Chiheb Abiza](https://github.com/chihebabiza)
