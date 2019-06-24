# Usage

Just run 
```sh
gookDown --input="input" --output="output"
```
to compile every local file referenced in the input file onto the new output one

## Example

Given the summary file at `summary.md`:
```md
# 1. Intro
- [Intro](./readme/intro.md)
# 2. Development
- [Development](./readme/development.md)
```
GookDown will compile the content of `Intro` and `Development` file into the new `README.md` file

This README was created using gookdown, look a fully example at this project's `readme` folder to futher understand gookdown 

## Options

To change the input and output files, pass it's flags
```
gookdown -input="./foo" -output="./bar"
```