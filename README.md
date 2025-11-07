# Push-swap
## Description
The push-swap algorithm takes a list of integers as an argument and sorts them efficiently with a limited amount of commands. The commands are printed as the output.
The checker program also takes a list of integers as an argument and also expects a list of simple commands as input. Then it checks if the provided commands correctly sort the list of integers.
See en.subject.pdf for a more detailed description.
## Requierements
- C Compiler
- `make` command
## Installation
- Clone the repository (e.g. `git clone https://github.com/Canteen43/push-swap`)
- Run `make` (or `make bonus` for the checker program)
## Usage examples
- `./pushswap 2 1 3`
- `ARG="4 67 3 87 23"; ./push_swap $ARG | ./checker_OS $ARG`
- `ARG=$(shuf -i 0-9999 -n 1000 | tr '\n' ' '); ./push_swap $ARG | ./checker $ARG`
## Visualizer
To get a cool visualization of the sorting, check out [this repo](https://github.com/o-reo/push_swap_visualizer).
## Acknowledgements
The exercise is part of the 42 core curriculum. en.subject.pdf is intellectual property of the [42 school](https://www.42network.org/).
