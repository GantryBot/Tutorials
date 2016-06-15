---
layout: post
title: Toggle Led
part: 1 of Serial Communication
description: Write data to Ardunio from qt widget. It is the first part of Serial communication tutorial. It covers writing to ardunio serially.
---

# {{ page.title }}

{{ page.description }}

{{ page.title }} shows how to toggle led on click of any keyboard button using the [QSerialPort](http://doc.qt.io/qt-5/qserialport.html)

Most of the focus would be on QTserial and QtSerailPort classes. I think validation each step for serial communication is take away here.


# Ardunio Setup:

Connect a Led Anode to pin 13 and cathode to pin GND.

# Ardunio Code 

{% gist 66cdfe20e8545213a4de6a125ff3dc64 %}
