# Final-OOP-Project
----------------------------------------------------------------------------------------------------------------------------
Tarcina 
TARCINA is designed to provide users with essential information 
and instructions on various methods for cleaning and purifying water
Explanation of the Code

Encapsulation: Each class (Boiling, Filtering, ChemicalTreatment) encapsulates 
its properties(like description) and provides public methods to access them.

Inheritance: The subclasses inherit from the abstract class WaterCleaning, 
promoting code reuse and creating a clear hierarchy of cleaning methods.

Polymorphism: The getInstructions method is overridden in each subclass to provide 
specific instructions for each type of water cleaning method.

Abstraction: The WaterCleaning class provides a common interface for all water 
cleaning methods without exposing the details of how each method is applied.

User Interaction
When the program runs, it presents a menu of water cleaning methods.
The user selects a method to view specific instructions on how to clean water safely.
The program continues to loop until the user chooses to exit by entering 0.

Error Handling
The program includes error handling for invalid menu choices and input parsing.
If a user inputs a non-integer value when prompted for a choice, the program will catch the exception and prompt the user again.

Conclusion
The Water Cleaning Management System demonstrates core OOP principles effectively while providing 
valuable information on how to ensure water safety through various cleaning methods. 
This example can be further expanded with additional cleaning methods, enhanced user interface features, 
or even integration with databases for storing user queries and feedback.
