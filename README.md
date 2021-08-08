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