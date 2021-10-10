# MyBus
Import ‘ package:flutter/material.dart’

Void main()
{
runApp(MyBus());
}

Class MyBus extends StatelessWidget
{
@override
Widget build(BuildContext context)
{
Return MaterialApp(
home: Scaffold(
backgroundcolor:colors.Blue,
body:Center(
child:Text(“MyBus”),
),
);
}
}


Text field - from and to

import 'package:flutter/material.dart';  
  void main() => runApp(MyApp());  
class MyApp extends StatelessWidget {  
   @override  
 Widget build(BuildContext context) {  
   return MaterialApp(  
    home: Scaffold(  
      appBar: AppBar(  
      title: Text("MyBus"),  
        ),  
        body: Container(  
          padding: EdgeInsets.all(35),  
          margin: EdgeInsets.all(20),  
          decoration: BoxDecoration(  
            border: Border.all(color: Colors.black, width: 4),  
            borderRadius: BorderRadius.circular(8),  
            boxShadow: [  
              new BoxShadow(color: Colors.blue, offset: new Offset(6.0, 6.0),),  
            ],  
          ),  
          child: Text("FROM:",  
              style: TextStyle(fontSize: 30)),  
        ),  
      ),  
    );  
  }  
}  
