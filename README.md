# 1st-Python-Notebook
{
  "metadata": {
    "language_info": {
      "codemirror_mode": {
        "name": "python",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.8"
    },
    "kernelspec": {
      "name": "python",
      "display_name": "Pyolite",
      "language": "python"
    }
  },
  "nbformat_minor": 4,
  "nbformat": 4,
  "cells": [
    {
      "cell_type": "markdown",
      "source": "Writing Your First Python Code\nEstimated time needed: 25 minutes\n\nObjectives\nAfter completing this lab you will be able to:\n\nWrite basic code in Python\nWork with various types of data in Python\nConvert the data from one type to another\nUse expressions and variables to perform operations",
      "metadata": {}
    },
    {
      "cell_type": "code",
      "source": "# Try your first Python output\nprint('Hello, Python!')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 27,
      "outputs": [
        {
          "name": "stdout",
          "text": "Hello, Python!\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Check the Python Version\nimport sys\nprint(sys.version)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 26,
      "outputs": [
        {
          "name": "stdout",
          "text": "3.10.2 (main, Apr  9 2022, 20:52:01) [Clang 14.0.0 (https://github.com/llvm/llvm-project 78e87970af888bbbd5652c31f3a8\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Practice on writing comments\nprint('Hello, Python') # this line prints a string\n#print('Hi')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 25,
      "outputs": [
        {
          "name": "stdout",
          "text": "Hello, Python\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print string as error message\nfrint(\"hello, Python!\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 24,
      "outputs": [
        {
          "ename": "<class 'NameError'>",
          "evalue": "name 'frint' is not defined",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "Cell \u001b[0;32mIn[24], line 2\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[38;5;66;03m# Print string as error message\u001b[39;00m\n\u001b[0;32m----> 2\u001b[0m \u001b[43mfrint\u001b[49m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mhello, Python!\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n",
            "\u001b[0;31mNameError\u001b[0m: name 'frint' is not defined"
          ],
          "output_type": "error"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print string and error to see the running order\n\nprint(\"This will be printed\")\nfrint(\"This will cause an error\")\nprint(\"This will NOT be printed\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 6,
      "outputs": [
        {
          "name": "stdout",
          "text": "This will be printed\n",
          "output_type": "stream"
        },
        {
          "ename": "<class 'NameError'>",
          "evalue": "name 'frint' is not defined",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mNameError\u001b[0m                                 Traceback (most recent call last)",
            "Cell \u001b[0;32mIn[6], line 4\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[38;5;66;03m# Print string and error to see the running order\u001b[39;00m\n\u001b[1;32m      3\u001b[0m \u001b[38;5;28mprint\u001b[39m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mThis will be printed\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n\u001b[0;32m----> 4\u001b[0m \u001b[43mfrint\u001b[49m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mThis will cause an error\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n\u001b[1;32m      5\u001b[0m \u001b[38;5;28mprint\u001b[39m(\u001b[38;5;124m\"\u001b[39m\u001b[38;5;124mThis will NOT be printed\u001b[39m\u001b[38;5;124m\"\u001b[39m)\n",
            "\u001b[0;31mNameError\u001b[0m: name 'frint' is not defined"
          ],
          "output_type": "error"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Write your code below. \nprint(\"Hello, world!\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 23,
      "outputs": [
        {
          "name": "stdout",
          "text": "Hello, world!\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Write your code below. \nprint(\"Hello, world!\") # Print the traditional hello world",
      "metadata": {
        "trusted": true
      },
      "execution_count": 22,
      "outputs": [
        {
          "name": "stdout",
          "text": "Hello, world!\n",
          "output_type": "stream"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of 96\ntype(96)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 18,
      "outputs": [
        {
          "execution_count": 18,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of 2.2698\ntype(2.2698)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 19,
      "outputs": [
        {
          "execution_count": 19,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of \"Hello, Python 101!\"\ntype(\"Hello, Python 101!\")",
      "metadata": {
        "trusted": true
      },
      "execution_count": 15,
      "outputs": [
        {
          "execution_count": 15,
          "output_type": "execute_result",
          "data": {
            "text/plain": "str"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of 12.0\ntype(12.0)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 20,
      "outputs": [
        {
          "execution_count": 20,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of -1\n\ntype(-1)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 28,
      "outputs": [
        {
          "execution_count": 28,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of 4\n\ntype(4)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 29,
      "outputs": [
        {
          "execution_count": 29,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of 0\n\ntype(0)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 30,
      "outputs": [
        {
          "execution_count": 30,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of 1.0\n\ntype(1.0) # Notice that 1 is an int, and 1.0 is a float",
      "metadata": {
        "trusted": true
      },
      "execution_count": 31,
      "outputs": [
        {
          "execution_count": 31,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of 0.5\n\ntype(0.5)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 32,
      "outputs": [
        {
          "execution_count": 32,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Print the type of 0.56\n\ntype(0.56)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 33,
      "outputs": [
        {
          "execution_count": 33,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# System settings about float type\n\nsys.float_info",
      "metadata": {
        "trusted": true
      },
      "execution_count": 34,
      "outputs": [
        {
          "execution_count": 34,
          "output_type": "execute_result",
          "data": {
            "text/plain": "sys.float_info(max=1.7976931348623157e+308, max_exp=1024, max_10_exp=308, min=2.2250738585072014e-308, min_exp=-1021, min_10_exp=-307, dig=15, mant_dig=53, epsilon=2.220446049250313e-16, radix=2, rounds=1)"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Verify that this is an integer\n\ntype(2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 35,
      "outputs": [
        {
          "execution_count": 35,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert 2 to a float\n\nfloat(2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 36,
      "outputs": [
        {
          "execution_count": 36,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert integer 2 to a float and check its type\n\ntype(float(2))",
      "metadata": {
        "trusted": true
      },
      "execution_count": 37,
      "outputs": [
        {
          "execution_count": 37,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Casting 1.1 to integer will result in loss of information\n\nint(1.1)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 38,
      "outputs": [
        {
          "execution_count": 38,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert a string into an integer\n\nint('1')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 39,
      "outputs": [
        {
          "execution_count": 39,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert a string into an integer with error\n\nint('1 or 2 people')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 40,
      "outputs": [
        {
          "ename": "<class 'ValueError'>",
          "evalue": "invalid literal for int() with base 10: '1 or 2 people'",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mValueError\u001b[0m                                Traceback (most recent call last)",
            "Cell \u001b[0;32mIn[40], line 3\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[38;5;66;03m# Convert a string into an integer with error\u001b[39;00m\n\u001b[0;32m----> 3\u001b[0m \u001b[38;5;28;43mint\u001b[39;49m\u001b[43m(\u001b[49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[38;5;124;43m1 or 2 people\u001b[39;49m\u001b[38;5;124;43m'\u001b[39;49m\u001b[43m)\u001b[49m\n",
            "\u001b[0;31mValueError\u001b[0m: invalid literal for int() with base 10: '1 or 2 people'"
          ],
          "output_type": "error"
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert the string \"1.2\" into a float\n\nfloat('1.2')",
      "metadata": {
        "trusted": true
      },
      "execution_count": 41,
      "outputs": [
        {
          "execution_count": 41,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1.2"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert an integer to a string\n\nstr(1)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 42,
      "outputs": [
        {
          "execution_count": 42,
          "output_type": "execute_result",
          "data": {
            "text/plain": "'1'"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert a float to a string\n\nstr(1.2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 43,
      "outputs": [
        {
          "execution_count": 43,
          "output_type": "execute_result",
          "data": {
            "text/plain": "'1.2'"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Value true\n\nTrue\n",
      "metadata": {
        "trusted": true
      },
      "execution_count": 47,
      "outputs": [
        {
          "execution_count": 47,
          "output_type": "execute_result",
          "data": {
            "text/plain": "True"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Value false\n\nFalse",
      "metadata": {
        "trusted": true
      },
      "execution_count": 48,
      "outputs": [
        {
          "execution_count": 48,
          "output_type": "execute_result",
          "data": {
            "text/plain": "False"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of True\n\ntype(True)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 49,
      "outputs": [
        {
          "execution_count": 49,
          "output_type": "execute_result",
          "data": {
            "text/plain": "bool"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Type of False\n\ntype(False)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 50,
      "outputs": [
        {
          "execution_count": 50,
          "output_type": "execute_result",
          "data": {
            "text/plain": "bool"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert True to int\n\nint(True)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 51,
      "outputs": [
        {
          "execution_count": 51,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert 1 to boolean\n\nbool(1)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 52,
      "outputs": [
        {
          "execution_count": 52,
          "output_type": "execute_result",
          "data": {
            "text/plain": "True"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert 0 to boolean\n\nbool(0)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 53,
      "outputs": [
        {
          "execution_count": 53,
          "output_type": "execute_result",
          "data": {
            "text/plain": "False"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Convert True to float\n\nfloat(True)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 54,
      "outputs": [
        {
          "execution_count": 54,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1.0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# What is the data type of the result of: 6 / 2?\ntype(6/2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 57,
      "outputs": [
        {
          "execution_count": 57,
          "output_type": "execute_result",
          "data": {
            "text/plain": "float"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# What is the type of the result of: 6 // 2? (Note the double slash //.)\ntype(6//2)",
      "metadata": {
        "trusted": true
      },
      "execution_count": 58,
      "outputs": [
        {
          "execution_count": 58,
          "output_type": "execute_result",
          "data": {
            "text/plain": "int"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Addition operation expression\n\n43 + 60 + 16 + 41",
      "metadata": {
        "trusted": true
      },
      "execution_count": 59,
      "outputs": [
        {
          "execution_count": 59,
          "output_type": "execute_result",
          "data": {
            "text/plain": "160"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Subtraction operation expression\n\n50 - 60",
      "metadata": {
        "trusted": true
      },
      "execution_count": 60,
      "outputs": [
        {
          "execution_count": 60,
          "output_type": "execute_result",
          "data": {
            "text/plain": "-10"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Multiplication operation expression\n\n5 * 5",
      "metadata": {
        "trusted": true
      },
      "execution_count": 61,
      "outputs": [
        {
          "execution_count": 61,
          "output_type": "execute_result",
          "data": {
            "text/plain": "25"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Division operation expression\n\n25 / 5",
      "metadata": {
        "trusted": true
      },
      "execution_count": 62,
      "outputs": [
        {
          "execution_count": 62,
          "output_type": "execute_result",
          "data": {
            "text/plain": "5.0"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Division operation expression\n\n25 / 6",
      "metadata": {
        "trusted": true
      },
      "execution_count": 63,
      "outputs": [
        {
          "execution_count": 63,
          "output_type": "execute_result",
          "data": {
            "text/plain": "4.166666666666667"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Integer division operation expression\n\n25 // 5",
      "metadata": {
        "trusted": true
      },
      "execution_count": 64,
      "outputs": [
        {
          "execution_count": 64,
          "output_type": "execute_result",
          "data": {
            "text/plain": "5"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Integer division operation expression\n\n25 // 6",
      "metadata": {
        "trusted": true
      },
      "execution_count": 65,
      "outputs": [
        {
          "execution_count": 65,
          "output_type": "execute_result",
          "data": {
            "text/plain": "4"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Let's write an expression that calculates how many hours there are in 160 minutes:\n160/60",
      "metadata": {
        "trusted": true
      },
      "execution_count": 70,
      "outputs": [
        {
          "execution_count": 70,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.6666666666666665"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# or\n160//60",
      "metadata": {
        "trusted": true
      },
      "execution_count": 71,
      "outputs": [
        {
          "execution_count": 71,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Mathematical expression\n\n30 + 2 * 60",
      "metadata": {
        "trusted": true
      },
      "execution_count": 72,
      "outputs": [
        {
          "execution_count": 72,
          "output_type": "execute_result",
          "data": {
            "text/plain": "150"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Mathematical expression\n\n(30 + 2) * 60",
      "metadata": {
        "trusted": true
      },
      "execution_count": 73,
      "outputs": [
        {
          "execution_count": 73,
          "output_type": "execute_result",
          "data": {
            "text/plain": "1920"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Store value into variable\n\nx = 43 + 60 + 16 + 41",
      "metadata": {
        "trusted": true
      },
      "execution_count": 76,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "# Print out the value in variable\nx",
      "metadata": {
        "trusted": true
      },
      "execution_count": 77,
      "outputs": [
        {
          "execution_count": 77,
          "output_type": "execute_result",
          "data": {
            "text/plain": "160"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Use another variable to store the result of the operation between variable and value\n\ny = x / 60\ny",
      "metadata": {
        "trusted": true
      },
      "execution_count": 78,
      "outputs": [
        {
          "execution_count": 78,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.6666666666666665"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Overwrite variable with new value\n\nx = x / 60\nx",
      "metadata": {
        "trusted": true
      },
      "execution_count": 79,
      "outputs": [
        {
          "execution_count": 79,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.6666666666666665"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Name the variables meaningfully\n\ntotal_min = 43 + 42 + 57 # Total length of albums in minutes\ntotal_min",
      "metadata": {
        "trusted": true
      },
      "execution_count": 80,
      "outputs": [
        {
          "execution_count": 80,
          "output_type": "execute_result",
          "data": {
            "text/plain": "142"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Name the variables meaningfully\n\ntotal_hours = total_min / 60 # Total length of albums in hours \ntotal_hours",
      "metadata": {
        "trusted": true
      },
      "execution_count": 81,
      "outputs": [
        {
          "execution_count": 81,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.3666666666666667"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# Complicate expression\n\ntotal_hours = (43 + 42 + 57) / 60  # Total hours in a single expression\ntotal_hours",
      "metadata": {
        "trusted": true
      },
      "execution_count": 82,
      "outputs": [
        {
          "execution_count": 82,
          "output_type": "execute_result",
          "data": {
            "text/plain": "2.3666666666666667"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# What is the value of x where x = 3 + 2 * 2",
      "metadata": {
        "trusted": true
      },
      "execution_count": 83,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "x= 3+2*2\nx",
      "metadata": {
        "trusted": true
      },
      "execution_count": 87,
      "outputs": [
        {
          "execution_count": 87,
          "output_type": "execute_result",
          "data": {
            "text/plain": "7"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# What is the value of y where y = (3 + 2) * 2?\nY=(3+2)*2\nY",
      "metadata": {
        "trusted": true
      },
      "execution_count": 88,
      "outputs": [
        {
          "execution_count": 88,
          "output_type": "execute_result",
          "data": {
            "text/plain": "10"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": "# What is the value of z where z = x + y?\nZ=x+Y\nZ",
      "metadata": {
        "trusted": true
      },
      "execution_count": 94,
      "outputs": [
        {
          "execution_count": 94,
          "output_type": "execute_result",
          "data": {
            "text/plain": "17"
          },
          "metadata": {}
        }
      ]
    }
  ]
}
