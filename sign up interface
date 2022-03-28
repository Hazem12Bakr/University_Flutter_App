import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      // Application name
      title: 'flutter App',
      // Application theme data, you can set the colors for the application as
      // you want
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      // A widget which will be started on application startup
      home: MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

class MyHomePage extends StatelessWidget {
  final String title;

  const MyHomePage({@required this.title});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
        appBar: AppBar(
          // The title text which will be shown on the action bar
          title: Text("sign up ", style: TextStyle(fontSize: 15)),
          centerTitle: true,
        ),
        body: SizedBox(
          width: double.infinity,
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            crossAxisAlignment: CrossAxisAlignment.center,
            children: [
              Container(
                  margin: EdgeInsets.symmetric(vertical: 27),
                  padding: EdgeInsets.symmetric(vertical: 5, horizontal: 9),
                  decoration: BoxDecoration(color: Colors.purple[100], borderRadius: BorderRadius.circular(66)),
                  width: 266,
                  child: TextField(
                    decoration: InputDecoration(
                      border: InputBorder.none,
                      hintText: "Your name : ",
                      hintStyle: TextStyle(fontSize: 19),
                      prefixIcon: Icon(Icons.info),
                    ),
                  )),
              Container(
                  margin: EdgeInsets.symmetric(vertical: 27),
                  padding: EdgeInsets.symmetric(vertical: 5, horizontal: 9),
                  decoration: BoxDecoration(color: Colors.purple[100], borderRadius: BorderRadius.circular(66)),
                  width: 266,
                  child: TextField(
                    keyboardType: TextInputType.number,
                    decoration: InputDecoration(
                      border: InputBorder.none,
                      hintText: "Your ID : ",
                      hintStyle: TextStyle(fontSize: 19),
                      prefixIcon: Icon(Icons.info),
                    ),
                  )),
              Container(
                  padding: EdgeInsets.symmetric(vertical: 5, horizontal: 9),
                  decoration: BoxDecoration(color: Colors.purple[100], borderRadius: BorderRadius.circular(66)),
                  width: 266,
                  child: TextField(
                    keyboardType: TextInputType.emailAddress,
                    decoration: InputDecoration(
                      border: InputBorder.none,
                      hintText: "Your E-mail : ",
                      hintStyle: TextStyle(fontSize: 19),
                      prefixIcon: Icon(Icons.person),
                    ),
                  )),
              Container(
                  margin: EdgeInsets.symmetric(vertical: 27),
                  padding: EdgeInsets.symmetric(vertical: 5, horizontal: 9),
                  decoration: BoxDecoration(color: Colors.purple[100], borderRadius: BorderRadius.circular(66)),
                  width: 266,
                  child: TextField(
                    obscureText: true,
                    decoration: InputDecoration(
                      border: InputBorder.none,
                      hintText: "Password : ",
                      hintStyle: TextStyle(fontSize: 19),
                      prefixIcon: Icon(Icons.lock),
                      suffixIcon: Icon(Icons.visibility),
                    ),
                  )),
              ElevatedButton(
                onPressed: () {},
                child: Text(
                  "Sign up",
                  style: TextStyle(fontSize: 10),
                ),
                style: ButtonStyle(
                  backgroundColor: MaterialStateProperty.all(Colors.purple),
                  padding: MaterialStateProperty.all(EdgeInsets.symmetric(horizontal: 95, vertical: 15)),
                  shape: MaterialStateProperty.all(RoundedRectangleBorder(borderRadius: BorderRadius.circular(66))),
                ),
              ),
            ],
          ),
        ));
  }
}
