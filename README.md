# Practice-6
Practice 6

import 'package:flutter/widgets.dart';

void main() => runApp(
  Directionality(
    textDirection: TextDirection.ltr,
    child: new Container(
      color: new Color(0xFFFFFFF),
      child: new Center(
        child: new Text(
          'Hello Flutter',
          style: new TextStyle(
            color: new Color(0xffff5252),
            fontSize: 32.0, fontWeight: FontWeight.bold,
          ),
        ),
      ),
    ),
  ),
);
