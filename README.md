# lesColors

lesColors is a lightweight Python package that provides utilities for manipulating and analyzing colors. It includes functions for calculating adjacent, analogous, and complementary colors, converting RGB values to hexadecimal format, and extracting the dominant color from an image via a URL.

## Installation

You can install LesColors via pip:

```bash
pip install lescolors
```

or

```bash
pip3 install lescolors
```

## Functions:
  - adjacent_colors:
      Calculates and returns the adjacent colors on the color wheel for a given RGB value.

  - analogous_colors:
      Computes and returns the analogous colors for a given RGB value.

  - complementary:
      Computes and returns the complementary color for a given RGB value.

  - rgb_to_hex:
      Converts an RGB color value to its hexadecimal (Hex) string format.

  - dominant_color_finder:
      Extracts and returns the most dominant RGB color from an image located at a given URL.
        
## Usage:
  This module can be used to explore color relationships, generate color schemes, and analyze colors from images. It is particularly useful for tasks related to dynamic theming, and visual content creation.

## Dependencies:
  - colorsys: A standard Python module for converting between color systems.
  - requests: A Python library for making HTTP requests.
  - colorthief: A library for grabbing the dominant color or a
              representative color palette from an image.

## Examples:
  - Finding analogous colors for a given RGB value:
      ```py3
      print(analogous_colors([255, 0, 0]))
      ```

  - Getting the complementary color of a given RGB value:
      ```py3
      print(complementary([255, 0, 0]))
      ```

  - Converting an RGB value to Hex format:
      ```py3
      print(rgb_to_hex([255, 0, 0]))
      ```

  - Finding the dominant color in an image:
      ```py3
      print(dominant_color_finder(image_url='https://i.stack.imgur.com/JM4F2.png', quality=1))
      ```

Have suggestions or issues? Let me know!
