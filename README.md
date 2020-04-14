# trip_cost_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# STATEFUL WIDGETS

## STATE
State is information that can be read synchronously when the widget is built and might change during the lifetime of the widget.  
Classes that inherit "StateFulWidget" are immutable. The State is mutable.

![image](https://user-images.githubusercontent.com/18363595/79238749-677daf00-7e8d-11ea-9dfd-361725218664.png)

## USING StateFul Widgets  
1. Creates a class that extends a Stateful Widgets, that return a State.  
2. Create a State class, with the properties that may change.  
3. Implement the build method.  
4. Call the setState() method to make changes.

`onChange`: Will change in real-time.  

`onSubmitted`: Will change once submitted.  

`hintText` in `InputDecoration` helps in adding placeholders.  

## Dropdowns
The `DropdownButton` widget has the generic type "T". It will have the type according to the type of data in your dropdown menu.  

## Input
While taking an input, you can also specify the keyboard type that should open using the `keyboardType` property of `TextField`. For example, if you want to take distance or amount as an input, it will always be a number. Thus, you can use `keyboardType: TextInputType.number`. Others can be email, phone number, urls, etc.  

[Theming the text input/text style](https://api.flutter.dev/flutter/material/TextTheme-class.html).  

Taking and saving a user's input in the text field can be done via 2 ways:  
1. Go with creating a variable and use the `onChange` event  
2. Use `TextEditingController`. It is like FormControl in Angular. Whenever a user modifies a text field with an associated `TextEditingController` the text field updates its value and the controller can notify any listners.  

It is a good practice to use constants for fixed spacing values like padding and margins.  


## Flex = Expanded
Expanded widget is used like a flex. Making Widgets as child elements of Expanded helps them to cover the space equally.  

## Colors
You can choose colors [here](https://api.flutter.dev/flutter/material/Colors-class.html).