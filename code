import 'package:flutter/material.dart';
void main() {
  runApp(MyTest());
}

class MyTest extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
          appBar: AppBar(
            centerTitle: true,
            title: Text("Dashboard"),
            backgroundColor: Colors.white,
            foregroundColor: Colors.red,
          ),
          body: Container(
            margin: EdgeInsets.all(40),
            height: 200,
            width: 300,
            decoration: BoxDecoration(
                color: Colors.red,
                border: Border.all(
                  color: Colors.red,
                ),
                borderRadius: BorderRadius.circular(10)),
            child: GridView.count(
              padding: new EdgeInsets.all(5),
              crossAxisCount: 2,
              crossAxisSpacing: 5,
              mainAxisSpacing: 5,
              children: <Widget>[
                Container(
                  height: 75,
                  decoration: BoxDecoration(
                      color: Colors.white,
                      border: Border.all(
                        color: Colors.white,
                      ),
                      borderRadius: BorderRadius.circular(10)),
                  child: Center(
                    child: Text(
                    "Balance",
                    textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Container(
                  height: 75,
                  decoration: BoxDecoration(
                      color: Colors.white,
                      border: Border.all(
                        color: Colors.white,
                      ),
                      borderRadius: BorderRadius.circular(10)),
                  child: Center(
                    child: Text(
                      "Profit Today",
                      textAlign: TextAlign.center
                    ),
                  ),
                ),
                Container(
                  height: 75,
                  decoration: BoxDecoration(
                      color: Colors.white,
                      border: Border.all(
                        color: Colors.white,
                      ),
                      borderRadius: BorderRadius.circular(10)),
                  child: Center(
                    child: Text(
                      "Stock"
                      , textAlign: TextAlign.center
                      ),
                  ),
                ),
                Container(
                  height: 75,
                  decoration: BoxDecoration(
                      color: Colors.white,
                      border: Border.all(
                        color: Colors.white,
                      ),
                      borderRadius: BorderRadius.circular(10)),
                  child: Center(
                    child: Text(
                      "Sold Today", 
                      textAlign: TextAlign.center,
                      )
                  ),
                ),
              ],
            ),
          )
        ),
    );
  }
}
