# Rebound

Rebound lets you instantly browse Stack Overflow search results in your terminal whenever you get a compiler error. Just use the `rebound` command before the file you want to execute.

![Placeholder Demo](demo.gif)

## Usage

Compiling a file with `rebound` is just as easy as running it normally:

`$ rebound [file_name]`

This will execute the file, pull the error message, and allow you to browse related Stack Overflow questions and answers without leaving the terminal. <!--Here's an example:-->

__Supported file types:__ Python, Node.js, Ruby, and Java.

## Installation

You can install rebound with pip:

`$ pip install rebound-cli`

Requires Python 3.0 or higher. MacOS, Linux, and Windows are all supported.

## Contributing

To make a contribution, fork the repo, make your changes and then submit a pull request. If you've discovered a bug or have a feature request, create an [issue](https://github.com/shobrook/rebound/issues/new) and tag it appropriately :)

## Technologies

Rebound is written in Python and built on Urwid. Beautiful Soup is used to scrape Stack Overflow content and subprocess for catching compiler errors.

## Acknowledgements

Special thanks to [@rndusr](https://github.com/rndusr) for helping with the scrollbar.
