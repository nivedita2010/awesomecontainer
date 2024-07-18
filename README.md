# Awesome Container
Awesome Container package let you add  a beautiful Awesome Container to your Flutter app.

## Installation
1.Add the latest version of package to your pubspec.yaml (and rundart pub get):
 ```yaml
dependencies:
 awesome_Container:^0.0.1
```
2. Import the package and use it in your flutter app.
   ```dart
   import 'package:awesomecontainer/awesome_conatiner.dart';
   ```


## Example
There are a number of properties that you can modify:

-  height
- width
- title
- subtitle
- gradient (color1 and color2)

<hr>

<table>
<tr>
<td>

dart
class GradientScreen extends StatelessWidget {  
const GradientScreen({Key? key}) : super(key: key);

@override  
Widget build(BuildContext context) {  
return Scaffold(  
body: Center(  
child: const AwesomeConatiner(  
title: 'Hello World',  
color1: Colors.lightGreenAccent,  
color2: Colors.lightBlue,  
subtitle: 'This is a new package',  
),  
),  
);  
}  
}


</td>
<td>
<img  src="https://user-images.githubusercontent.com/53579386/126896556-911d4778-04cd-49bf-b32a-01a6eb3b0155.jpeg"  alt="">
</td>
</tr>
</table>

## Next Goals

- [x] Add onTap for functions.
  Now, you can specify the onTap and specify a function.

- [x] Change font and color style for text.
  Change color by specifying `textcolor` and `subtitlecolor` properties.

- [ ] Add more containers to the package.


