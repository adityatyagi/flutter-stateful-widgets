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

### Dropdowns
The `DropdownButton` widget has the generic type "T". It will have the type according to the type of data in your dropdown menu.  



