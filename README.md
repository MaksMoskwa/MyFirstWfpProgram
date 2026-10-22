AplikacjaWpf – Counter
Project Description

AplikacjaWpf is a simple desktop application written in C# using WPF (Windows Presentation Foundation). The application allows users to perform mathematical operations on a counter using buttons in a graphical user interface.

Features

The application provides the following counter operations:

Increment by 1 – increases the counter value by one.
Decrement by 1 – decreases the counter value by one.
Increment by 29013 – adds 29013 to the current counter value.
Divide by 27 – divides the current counter value by 27.
Multiply by 4 – multiplies the current counter value by 4.
Reset – sets the counter value to zero.

The result of each operation is displayed in the CounterBlock element.

Technologies
C# – programming language.
WPF (Windows Presentation Foundation) – framework for building desktop applications.
XAML – language used to define the graphical user interface.
.NET – application development and runtime platform.
Project Structure
App.xaml – contains the WPF application configuration.
App.xaml.cs – contains the main application class.
MainWindow.xaml – defines the graphical user interface.
MainWindow.xaml.cs – contains the application logic, counter operations, and button event handlers.
README.md – project documentation.
How to Run the Application
Open the project in Visual Studio.
Open the solution file (.sln) or the project file (.csproj).
Wait for the project to load and any required packages to be restored.
Run the application by pressing F5 or clicking the Start button.
How It Works

The counter value is stored in an integer variable named count of type int. When a button is clicked, the corresponding mathematical operation is performed, and the displayed value is updated.

Division by 27 uses integer division because the count variable is of type int. This means that any fractional part of the result is discarded.

Project Objective

The objective of this project is to learn the fundamentals of developing desktop applications with WPF, handling events in C#, and updating graphical user interface elements based on variables and mathematical operations.
