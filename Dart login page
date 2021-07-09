import 'package:flutter/cupertino.dart';
import 'package:flutter/material.dart';


void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(

      debugShowCheckedModeBanner: false,
      title: 'Flutter Demo',
      theme: Themedata(
        primarySwatch: Colors.blue,
      ), //themedata

      home: MyHomePage(title: 'Flutter login'),

    );
  }
}

class Themedata {
}

class MyHomePage extends StatefulWidget {
  MyHomePage({Key key, this.title}) :super (key: key);
  final String title;

  _MyHomePageState createState() => _MyHomePageState extends

  StatefulWidget();

}

class _MyHomePageState extends StatefulWidget {
  TextStyle style = TextStyle(fontFamily: 'Montserrat', fontSize: 20.0);

  @override
  widget build

  (

  BuildContext.context

  ){
  final emailField= TextField(
  obscureText: false,
  style: style,
  decoration: InputDecoration(
  contentPadding: EdgeInsets.fromLTRB(20.0, 15.0, 20.0, 15.0),
  hintText: "Email",
  border:
  OutlineInputBorder(borderRadius: BorderRadius.circular(32.0)),
  )
  );
  final passwordField= TextField(
  obscureText: true,
  style: style,
  decoration: InputDecoration(
  contentPadding: EdgeInsets.fromLTRB(20.0, 15.0, 20.0, 15.0),
  hintText: "password",
  border:
  OutlineInputBorder(borderRadius: BorderRadius.circular(32.0)),
  )
  );

  final loginButton = material(
  elevation :5.0,
  borderRadius: BorderRadius.circular(30.0),
  color:Color(0xff01A0C7),
  child: MaterialButton(
  minWidth: MediaQuery.of(context).size.width,
  padding: EdgeInsets.fromLTRB(20.0, 15.0, 20.0, 15.0),
  onPressed:(){}
  child:Text("Login",
  textAlign: TextAlign.center),
  style:style.copyWith(color.white,fontWeight: FontWeight.bold ),//text

  ),
  );//Material
  return Scaffold(
  body: SingleChildScrollView(
  child:Center(
  child: Container(
  color: Colors.White,
  child:Padding(
  padding:const EdgeInsets.all(36.0),
  child:Column(
  crossAxisAlignment: CrossAxisAlignment.center,
  mainAxisAligment : MainAxisAlignment.center,
  children:<Widget>[
  SizedBox(
  height:155.0
  child: Image.asset("assets/logo.png",
  fit:Boxfit.contain,),
  ),
  SizedBox(
  height: 45.0),
  emailField,
  SizedBox(
  height: 25.0),
  passwordField,
  SizedBox(
  height: 35.0),
  loginButton,
  SizedBox(
  height:15.0
  ),

  ],
  ),
  ),
  ),
  ),
  ),
  );
  }
}
