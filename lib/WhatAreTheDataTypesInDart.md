# Data types in Dart programming

Dart is a programming language that is statically typed; this means that variables always have the same type, which cannot be changed.

Data types in Dart programming are given below:

- Numbers
- Strings
- Booleans
- Lists
- Maps

## Numbers

In Dart, numbers are used to represent numeric literals. Dart numbers are grouped into two types:

- **Integer**: represents non-fractional numbers (whole numbers). Integers can be declared with the `int` keyword.

- **Double**: represents fractional numbers (floating-point numbers). Doubles can be declared with the `double` keyword.

```dart
    void main() {
        //declare a integer value
        int num1 = 1;
        // declare a double value
        double num2 = 1.5;
        print(num1);
        print(num2);
    }
```

## Strings

A string represents string literals and is a sequence of characters. A `string` is declared with the String keyword.

```dart

    void main() {
        String str = 'Educative';
        print(str);
    }
```

## Booleans

A boolean represents true and false values. It is declared with the bool keyword.

```dart
    void main() {
    bool val = true;
    print(val);
    }
```

## Lists

A list is used to represent a collection of objects. It is similar to the concept of an array in other programming languages. A list is a group of ordered objects.

```dart
    void main()
    {
        List shot = List(3);
        shot[0] = 'Data types';
        shot[1] = 'in';
        shot[2] = 'Dart';
        print(shot);
        // access the first index
        print(shot[0]);
    }
```

## Maps

A map is a dynamic collection that represents a set of values as key-value pairs. Keys and values on a map may be of any type.

```dart
void main()
{
    Map shot =  Map();
    shot['0'] = 'Data types';
    shot['Second'] = 'in';
    shot['a'] = 'Dart';
    print(shot);
}
```
