
[![Arduino CI](https://github.com/RobTillaart/Angle/workflows/Arduino%20CI/badge.svg)](https://github.com/marketplace/actions/arduino_ci)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/RobTillaart/Angle/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/RobTillaart/Angle.svg?maxAge=3600)](https://github.com/RobTillaart/Angle/releases)


# Angle

Arduino library for basic math for Angles in degrees, minute, seconds and tenthousands.

## Description

Angle is an Arduino class to print, compare and do basic math with angles
in degrees, minutes seconds and tenthousands. The class was created to be
able to print an angle with minutes and seconds instead of as a floating point
or radians.

To make the library more useful basic math ( + - \* / ) 
and comparisons ( == != < <= > >= ) are added to the class.

## Interface

There are three constructors
- **Angle(int dd=0, int mm=0, int ss=0, int tt=0)**
- **Angle(double alpha)**
- **Angle(char \* str)**       // str represents a double as string e.g. "45.31234"

## Operation

See examples


## Note
The library has not been tested extensively and it could still contain
bugs. Especially the constructor does not check input so use it carefully.
