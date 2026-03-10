import 'package:flutter/material.dart';
import 'screens/home_screen.dart';

void main() {
  runApp(MasterPodRukoyApp());
}

class MasterPodRukoyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'МастерПодРукой 24/7',
      debugShowCheckedModeBanner: false,
      theme: ThemeData(primarySwatch: Colors.blue),
      home: HomeScreen(),
    );
  }
}
