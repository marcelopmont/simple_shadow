# simple_shadow

A customizable shadow for any widget

## Getting Started

import:
``` dart
import 'package:simple_shadow/simple_shadow.dart';
```

example:
```dart
SimpleShadow(
    child: Image.asset('images/bird.png'),
    opacity: 0.6,         // Default: 0.5
    color: Colors.blue,   // Default: Black
    offset: Offset(5, 5), // Default: Offset(2, 2)
    sigma: 7,             // Default: 2
)
```
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/example.png)

### Default
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/default.png)

### Color: Colors.blue
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/color_blue.png)

### Opacity: 1
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/opacity_1.png)

### Sigma: 10
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/sigma_10.png)

### Offset: Offset(10, 10)
![](https://github.com/marcelopmont/simple_shadow/blob/main/screenshots/offset_10.png)

