class HelloWorld extends StatefulWidget {
  @override
  HelloWorldState createState() => HelloWorldState();
}

class HelloWorldState extends State<HelloWorld> {

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Text("Hello World"),
    );
  }
}
