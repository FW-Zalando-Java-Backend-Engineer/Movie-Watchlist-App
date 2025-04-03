# 🎯 **Assignment: Build Your Movie Watchlist App with ArrayList**

Welcome to your next Java assignment! In this challenge, you’ll build a **Movie Watchlist Manager** using **Java's `ArrayList`**.

---

## 📘 **Overview**

Everyone loves movies, right? In this assignment, you’ll simulate a **movie tracking app** where users can:
- Add movies they want to watch
- Remove watched movies
- View their current watchlist
- Count how many movies are still on the list

This is a great chance to practice working with Java's **ArrayList**, **user input**, and **basic list operations**.

---

## 🛠️ **Learning Objectives**

By completing this assignment, you’ll learn how to:
- Use `ArrayList` to manage dynamic collections
- Add, remove, and access elements
- Work with `Scanner` for user interaction
- Build a menu-driven Java application

---

## 🧩 **Requirements**

### Implement a class called `MovieWatchlistApp` that includes:
- An `ArrayList<String>` to store movie titles.
- A **menu** that allows users to:
  1. Add a movie
  2. Remove a movie
  3. View all movies
  4. Count movies
  5. Exit the app

### 🧪 Example Flow
```
🎬 Welcome to your Movie Watchlist!

1. Add a movie
2. Remove a movie
3. View watchlist
4. Count movies
5. Exit

👉 Choose an option: 1
🎥 Enter movie name: Inception
Inception added to watchlist!

👉 Choose an option: 3
📽️ Your Watchlist:
1. Inception

👉 Choose an option: 4
🎞️ Total movies in watchlist: 1
```

---

## 📁 **Project Structure**
```bash
MovieWatchlistApp/
├── MovieWatchlistApp.java   # Your main class
├── README.md                # (Optional) Write your own description
```

---

## 📌 **Bonus Points (Optional Enhancements)** 💡
✅ Prevent duplicate movie entries  
✅ Allow removing movies by index  
✅ Sort movies alphabetically  
✅ Save and load the watchlist using a file

---

## 🚀 **Submission Guidelines**
- Clone the assignment repo in GitHub Classroom.
- Implement your solution in the `MovieWatchlistApp.java` file.
- Commit and push your code.
- Make sure it compiles and runs without errors.
- Submit before the due date 🎯

---

## 🧑‍💻 Starter Template

You can use this as a starting point in your `main` method:

```java
import java.util.ArrayList;
import java.util.Scanner;

public class MovieWatchlistApp {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        ArrayList<String> watchlist = new ArrayList<>();

        // Your menu logic here

        scanner.close();
    }
}
```

---

## 🧠 Need Help?
- Check out the [Java ArrayList Docs](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html)
- Or reach out in the class forum! Don’t suffer in silence – that’s for PHP devs 😅

---

**Good luck, and happy movie hunting! 🎬🍿**
