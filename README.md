📘 Course Outcome Management System (OBE Implementation)

This project is a Course Outcome Management System built as part of the CS204: Design and Analysis of Algorithms (DAA) course project.
It helps manage Course Outcomes (COs) using CRUD operations and demonstrates the practical use of sorting and searching algorithms with real-time comparisons.

The system stores all course outcome records in a text file (course_outcome.txt) to ensure data persistence across executions. 


🚀 Features

    ✅ Create Course Outcome
    ✅ Retrieve (View) Course Outcomes
    ✅ Update Course Outcome
    ✅ Delete Course Outcome
    ✅ Store data persistently in file (course_outcome.txt) 

🔍 Searching Algorithms Implemented

  • Linear Search — O(n)
  
  • Binary Search — O(log n) (requires sorting)

📌 Sorting Algorithms Implemented

  • Bubble Sort — O(n²)
  
  • Quick Sort — O(n log n) (average case)

The project also includes algorithm comparison options for better understanding of efficiency. 


🏗️ Module: Course Outcome Management

Each Course Outcome is stored with the following fields: 

    Field Name	    Data Type
    cour_out_code	   String
    cour_id	         String
    bloom_id	       String
    e_proficiency	   Float
    e_attainment	   Float

🛠️ Tech Stack

• Language: C

  • Concepts Used:

      Structures
      
      File Handling
      
      Sorting Algorithms
      
      Searching Algorithms
      
      Time Complexity Analysis

📂 Files Included

    OBE_MAIN_Team_unity.c → Main source code file
    
    course_outcome.txt → Stores saved course outcomes
    
    OBE_Project_Report_Team_unity.docx → Full project documentation
    
    OBE_Team_unity_course_outcome.pptx → Presentation slides

⚙️ How to Run
✅ Compile the Program

    gcc OBE_MAIN_Team_unity.c -o course_outcome

✅ Execute

    ./course_outcome


(Windows)

    course_outcome.exe

📌 Menu Options (System Workflow)

The program provides options such as: 
    
    Create Course Outcome
    
    Update Course Outcome
    
    Retrieve Course Outcomes
    
    Delete Course Outcome
    
    Sort (Bubble Sort / Quick Sort)
    
    Search (Linear Search / Binary Search)
    
    Show Time Complexity
    
    Display Algorithm Details
    
    Store Records into File
    
    Exit

🎯 Project Objective

This project is designed to:

• Implement an Outcome-Based Education (OBE) management module

• Demonstrate CRUD operations using structured data

• Compare sorting & searching algorithms in a real application setting

• Maintain records using file persistence for repeated usage 

✅ Conclusion

  The Course Outcome Management System provides an efficient way to create, store, retrieve, update, and delete Course Outcomes while showcasing real implementations of sorting and searching algorithms. It also    highlights algorithm complexity comparisons in practical scenarios. 
