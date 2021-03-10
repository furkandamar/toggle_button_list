# toggle_button_list

Create custom toggle button list

<img src="https://raw.githubusercontent.com/furkandamar/toggle_button_list/main/Screenshot_1615376825.png" height="500" />

## Installation

pubspec.yaml : 
```
dependencies : 
    toggle_button_list: ^0.0.2
    
```
## Example
### Basic  
```dart
ToggleButtonList(items: ["Furkan", "Burak", "Yusuf", "Mami"],activeColor: Colors.green, defaultColor: Colors.black12);
```

### Add horizontal list 
listType: ListType.Horizontal
```dart
ToggleButtonList(items: ["Furkan", "Burak", "Yusuf", "Mami"],activeColor: Colors.green, defaultColor: Colors.black12,listType: ListType.Horizontal);
```

### Add vertical list 
listType: ListType.Vertical
```dart
ToggleButtonList(items: ["Furkan", "Burak", "Yusuf", "Mami"],activeColor: Colors.green, defaultColor: Colors.black12,listType: ListType.Vertical);
```

### Set default index 
selectedIndex: (number)
```dart
ToggleButtonList(items: ["Furkan", "Burak", "Yusuf", "Mami"],activeColor: Colors.green, defaultColor: Colors.black12,selectedIndex: 2);
```

### OnTap event 
onTap: (selectedIndex)
```dart
ToggleButtonList(items: ["Furkan", "Burak", "Yusuf", "Mami"],activeColor: Colors.green, defaultColor: Colors.black12,listType: ListType.Horizontal, onTap: (selected) {
    this.setState(() {
      print(selected);
    });  
  });
```
