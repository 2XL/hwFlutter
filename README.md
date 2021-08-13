# hwFlutter


@[Flutter Studio](https://flutterstudio.app/) => fast prototyping

@ Everything is a Widget.

 - stateful: stless ->
 - stateless: atful ->
 - animations: stanim
 
@ GestureDetector Widget. - - widget tat detects gestures
 ```dart
(
    onTap: (){}
    onDoubleTap: (){}
    onLongPress: (){}  
 ){}
```
 
@ Animations.   
  - tweens
  - physics
  
@ State is information that might change during the lifetime of the widget
  
@ Streams .sink=> ]  pipe  [ =>.stream 
@Listener StreamSubscription -> @StreamTransformer


BL o C Pattern  => design Pattern 



@[packages for](https://pub.dartlang.org) 
- media
- network
- sensors
- video streaming
- databases


@flutter packages at 
 - [pub.dev](pub.dev) 130 reliability cap 100% compatibility cap
 

@localizations
- internalization (24lang)
```yaml 

- pubspec.yaml
- for each lang, create .arb files localize class

```


@Testing
- automatized tests (TDD)
Unit Tests
Widget Tests
Integration Tests -> real device / emulator, app works as a whole
```dart


import 'package:tests/test.dart';
void main(){}
test('my test', (){
 var myText = 'hello';
 expect(myText, 'hello')
})




```

@Dard Playground -> [DartPad](dartpad.dev)




@Flutter navigation

```
declarative

imperative
```

@Drawer

@ListView
a list that scrolls horizontally or vertically


@Scaffold

@Navigator -> stack 
 .push(route)
 .pop()
 
 deck
 
 
@State -> is information that can be used when the widget is build and might change during the lifetime of the widget

Stateless -> does not a mutable state -> override build()
Use when the UI depends on information in the object itself

Stateful -> has mutable state -> override createState() -> return State() -> recursive function
Use when the UI can change dynamically


@null
later
?
??