# animated_horizontal_calendar

A flutter plugin to show animated horizontal view of calendar with date picker.

# Features #
- Seperate Date picker Component.
- CustomShape and style  for Selected Item.
- CustomShape and style  for unSelected Item.
- Swipe behavior,not list.

## Getting Started

This project is a starting point for a Flutter
[plug-in package](https://flutter.dev/developing-packages/),
a specialized package that includes platform-specific implementation code for
Android and/or iOS.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
## depandancy packeges
- intl
## App Demo

![](app.gif)

## Example
This plugin allow you to do custom styles and shapes for Selected and UnSelected dates
```dart
    AnimatedHorizontalCalendar(
        date: DateTime.now(),
        textColor: Colors.black45,
        backgroundColor: Colors.white,
        selectedColor: Color(0xff092B47),
        iconColor: Colors.white,
        onDateSelected: (date){
           selectedDate = date;
       } 
    ),
```
