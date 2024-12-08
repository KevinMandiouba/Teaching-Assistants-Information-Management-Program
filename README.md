# 🧑‍🏫 TAs Information Management Program 📚

Welcome to the Teaching Assistants Information Management Program! This project simplifies the management of Teaching Assistants (TAs) by providing functionalities to add, modify, sort, and retrieve TA information. It's designed as a hands-on demonstration of programming methodologies using C++.

---

## 🌟 Features

- Efficient Data Management: Read and write TA data from a file (TAs.txt).
- Validation & Error Handling: Ensures all inputs are accurate and valid (e.g., prevents duplicate IDs or invalid statuses).
- Dynamic Sorting Options: Allows sorting by ID, status, year hired, or working hours, in ascending or descending order.
- Interactive Interface: Provides a user-friendly menu-driven interface.

---

## 📂 Project Structure

### 📜 Core Files

- TAs.h: Header file defining the TAs class and its methods.
- TAs.cpp: Implementation of the TAs class methods.
- Driver.cpp: Main program file providing the interactive interface.
- TAs.txt: Initial data file containing a list of TAs.

### 📝 Example Data (TAs.txt)
```plaintext
5  
3222853  Alum    2014    5  
5905370  Grad    2015    13  
1562433  Alum    2015    6  
8207152  Grad    2021    11  
6071500  Grad    2019    14
```

---

## 🚀 Getting Started

### Prerequisites

- C++ Compiler: Ensure you have a C++ compiler like g++.
- Standard Template Library (STL): Supported by your compiler.

### Installation & Usage

1. Clone the repository:
   `git clone https://github.com/KevinMandiouba/Teaching-Assistants-Information-Management-Program.git`
2. Navigate to the project directory:
   `cd Teaching-Assistants-Information-Management-Program`
3. Compile the program:
   `g++ -o main Driver.cpp TAs.cpp`
4. Run the program:
   `./main`

---

## 🛠️ Program Workflow

1. Load Initial Data: Automatically reads TAs.txt into the program and validates entries.
2. Interactive Menu:
   - Add New TAs: Enter details for new TAs, ensuring no duplicate IDs or invalid statuses.
   - Sort TA Records: Choose a sorting field and order (ascending/descending).
   - Exit: Safely saves data back to TAs.txt and exits the program.

---

## 🌐 Future Enhancements

- Add search functionality for specific TA records.
- Implement a graphical user interface (GUI).
- Allow exporting reports in different formats (CSV, JSON).

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit pull requests. For major changes, please open an issue to discuss your ideas.

---

## 📜 License

This project is licensed under the MIT License.

---

### ✨ Developed as part of the Programming Methodology II course. 
