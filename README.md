# Saber-print

If you know basic HTML and CSS, then you can start creating books with saber-print.

## example

https://ahmed0saber.github.io/saber-print/example/

# Saber-Print Library

## Introduction

Saber-Print is a powerful and easy-to-use Python library for generating formatted text output. It provides a variety of methods to format and print text in a visually appealing and structured manner. Whether you need to create fancy headers, highlight important information, or align columns, Saber-Print has got you covered.

## Installation

You can install Saber-Print using pip:

```
pip install saber-print
```

## Usage

To use Saber-Print in your Python project, you need to import the library:

```python
import saber_print
```

Once imported, you can access the various formatting and printing functions provided by the library.

### Printing Text

The `print_text()` function is used to print formatted text. It takes a string as input and supports various formatting options, such as headers, highlighting, and alignment.

Here's an example that demonstrates the basic usage of `print_text()`:

```python
saber_print.print_text("Hello, Saber-Print!")
```

Output:

```
Hello, Saber-Print!
```

### Headers

You can create headers using the `print_header()` function. It takes a string as input and prints it as a formatted header.

```python
saber_print.print_header("Welcome to Saber-Print")
```

Output:

```
=============================
Welcome to Saber-Print
=============================
```

### Highlighting Text

To highlight specific text, you can use the `print_highlighted()` function. It takes a string as input and prints it with a highlighted style.

```python
saber_print.print_highlighted("Important Information")
```

Output:

```
*** Important Information ***
```

### Alignment

You can align text using the `print_aligned()` function. It takes a list of strings as input and prints them in aligned columns.

```python
data = [
    ["Name", "Age", "Country"],
    ["John", "25", "USA"],
    ["Emily", "32", "Canada"],
    ["Mark", "18", "Australia"]
]

saber_print.print_aligned(data)
```

Output:

```
Name   Age  Country
John   25   USA
Emily  32   Canada
Mark   18   Australia
```

### Customization

Saber-Print provides several customization options to modify the appearance of the printed text. You can set the colors, styles, and other formatting options by configuring the library.

Here's an example of changing the text color:

```python
saber_print.set_text_color("blue")
saber_print.print_text("Hello, Saber-Print!")
```

Output:

```
[Blue] Hello, Saber-Print!
```


## License

Saber-Print is released under the [MIT License](LICENSE).

## Acknowledgments

Saber-Print was inspired by the need for a simple and flexible text printing library. We would like to acknowledge the contributions of the open-source community and the various libraries that inspired this project.

## Contact

For any questions or suggestions, please contact the Saber-Print development team.
