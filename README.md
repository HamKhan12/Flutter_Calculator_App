# Flutter Calculator App

A beautiful and functional calculator application built with Flutter, featuring a clean user interface and advanced mathematical capabilities.

##Screenshot
![WhatsApp Image 2025-08-27 at 5 21 57 PM](https://github.com/user-attachments/assets/a8c121ab-8719-4b85-a9fc-b7f8454ef934)


## Features

- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division
- **Percentage Calculations**: Quick percentage calculations
- **Sign Change**: Positive/Negative number toggle
- **Decimal Support**: Support for floating-point numbers
- **Clear Function**: AC (All Clear) button to reset calculations
- **Delete Function**: DEL button to remove last entered character
- **Real-time Display**: Shows both current input and calculated results
- **Modern UI**: Clean, iOS-inspired design with orange accent buttons

## Technical Implementation

### Dependencies
This app uses the following packages:
- `math_expressions`: For parsing and evaluating mathematical expressions

### Project Structure
The app follows a component-based architecture:
- `HomeScreen`: Main calculator screen with state management
- `MyButton`: Reusable button component for the calculator interface

### Key Components

#### HomeScreen
- Manages the calculator state using `StatefulWidget`
- Displays user input and calculated results
- Handles button press events and updates UI accordingly

#### MyButton
- Custom button widget with consistent styling
- Supports different colors for numeric and operation buttons
- Accepts title and onPress handler as parameters

## Installation

1. Ensure you have Flutter installed on your system
2. Clone this repository
3. Add the required dependency to your `pubspec.yaml`:
   ```yaml
   dependencies:
     math_expressions: ^latest_version
   Run flutter pub get to install dependencies
4. Connect a device or emulator and run flutter run

##Usage

1. Tap number buttons to enter values
2. Use operation buttons (+, -, ×, ÷) to perform calculations
3. Press '=' to evaluate the expression
4. Use 'AC' to clear all inputs or 'DEL' to remove the last character
5. The '%' button calculates percentages
