# Context-Free Grammar First & Follow Calculator

This project is a web-based tool for calculating the First and Follow sets of a context-free grammar (CFG). It takes user input in the form of a CFG and computes these sets, showing the results with a typewriter animation.

## Features

- **Grammar** Input: Input context-free grammar in a textarea with production rules.
- **Symbols**: Use buttons or shortcut keys to input symbols like →, |, and λ.
- **Syntax Checking**: Basic validation to check if the grammar syntax is correct.
- **First & Follow Calculation**: Computes the First and Follow sets using predefined rules.
- **Typewriter Animation**: Displays results in a typewriter style for a better user experience.

## Usage

1. Enter the grammar in the text area in the format:

```
S → ACB | Cbb | Ba
A → da | BC
B → g | λ
C → h | λ
```

2. Use shortcuts to insert special symbols:

- **1**:**→**
- **2**:**|**
- **3**:**λ**

3. Press the Check Grammar button to calculate the First and Follow sets.

## Installation

1. Clone the repository:

```
git clone https://github.com/RezaTaheri01/first-follow-compiler.git

```

2. Open index.html in your browser.

## License

This project is licensed under the MIT License.
