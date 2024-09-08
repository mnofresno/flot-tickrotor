# flot-tickrotor

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Overview

`flot-tickrotor` is a Flot plugin that allows you to display angled X-axis tick labels in your charts. This feature is particularly useful for improving readability when dealing with long or overlapping labels.

## Features

- Rotate X-axis tick labels to any angle for better visibility.
- Easy integration with existing Flot charts.
- Lightweight and simple to use.

## Installation

You can install `flot-tickrotor` using Bower or by including the script directly in your project.

### Using Bower

To install via Bower, run the following command:

bower install flot-tickrotor

### Manual Installation

Alternatively, you can download the `jquery.flot.tickrotor.js` file from the [releases page](https://github.com/markrcote/flot-tickrotor/releases) and include it in your project.

<script src="path/to/jquery.flot.tickrotor.js"></script>

## Usage

To use the `flot-tickrotor` plugin, simply call it on your Flot chart as follows:

$(function() {
    var data = [[0, 0], [1, 1], [2, 4], [3, 9], [4, 16]];
    
    $.plot("#placeholder", [data], {
        xaxis: {
            ticks: [[0, "Zero"], [1, "One"], [2, "Two"], [3, "Three"], [4, "Four"]],
            tickRotation: 45 // Set the rotation angle here
        }
    });
});

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue on GitHub. You can also fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- [Mark R. Cote](https://github.com/markrcote)
- [M. No Fresno](https://github.com/mnofresno)

## Homepage

For more information, visit the [flot-tickrotor homepage](https://github.com/markrcote/flot-tickrotor).
