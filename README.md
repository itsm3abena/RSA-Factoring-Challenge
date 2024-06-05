
# RSA Factoring Challenge

## Description
This project implements an RSA factoring challenge. The RSA encryption algorithm relies on the difficulty of factoring large prime numbers to ensure the security of encrypted communication. This challenge provides an opportunity for participants to test their factoring algorithms against a set of RSA keys.

## Features
- Implements RSA factoring challenge.
- Uses a C library for efficient prime factorization.
- Accepts input files containing RSA keys to factorize.

## Requirements
- Python 3
- C compiler


## Installation
1. Clone this repository: `git clone https://github.com/itsm3abena/RSA-Factoring-Challenge.git`
2. Compile the C library: `gcc -shared -o lib_factors_functions.so factors_functions.c`
3. Run the program: `python3 rsa.py <input_file>`

## Usage
To use this challenge, follow these steps:
1. Prepare an input file containing RSA keys to factorize. Each key should be on a separate line.
2. Run the program with the input file as an argument: `python3 rsa.py input.txt`
3. The program will output the factors for each RSA key in the input file.

## Example
Suppose you have an input file `keys.txt` containing RSA keys:
```
12345678910111213141516171819202122232425262728293031
32333435363738394041424344454647484950515253545556557

```
will output the factors for each key.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
