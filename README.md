# Autoficate

A simple template for automating certificate generation.

## Quick Start

1. Clone this repository
2. Open `config.ini` in your editor
3. Modify the following values according to your needs:
   - `x`: X-coordinate for text placement
   - `y`: Y-coordinate for text placement
   - `font_size`: Size of the font
   - `alignment`: Text alignment (left, center, right)

## Configuration

The `config.ini` file contains all the settings you need to customize:

```ini
[Certificate]
# X and Y coordinates for text placement
x = 100
y = 200

# Font settings
font_size = 24
alignment = center
```

That's it! You only need to change these values to customize your certificates.

## Usage

Run the application:

```bash
python main.py
```

## License

MIT License - See LICENSE file for details
