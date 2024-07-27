# Image to ASCII Converter

This is a simple Image to ASCII Converter built using Python and Tkinter. It allows users to upload an image and convert it into ASCII art.

## Features

- **Upload Image**: Upload an image file using a graphical user interface.
- **Convert to ASCII**: Convert the uploaded image to ASCII art.
- **Display ASCII Art**: Display the generated ASCII art in a text area within the GUI.

## Requirements

- Python 3.x
- Pillow (Python Imaging Library)
- Tkinter (usually included with Python)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/image-to-ascii-converter.git
    cd image-to-ascii-converter
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    ```

    - On Windows:
      ```bash
      .\venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```

3. **Install the required libraries**:
    ```bash
    pip install pillow
    ```

## Usage

1. **Run the application**:
    ```bash
    python img_to_ascii.py
    ```

2. **Upload an image**:
    - Click the "Upload Image" button to select an image file.
    - The ASCII art of the uploaded image will be displayed in the text area.

## How It Works

- The application uses the Pillow library to handle image processing.
- The image is resized to maintain the aspect ratio and then converted to grayscale.
- Each pixel's intensity is mapped to an ASCII character based on its brightness.
- The ASCII art is displayed in a text area within the Tkinter GUI.

## Code Structure

- `img_to_ascii.py`: The main script containing the application logic and GUI setup.


### Before
![Original Image] (https://github.com/user-attachments/assets/b9ca3c26-048e-4707-966d-0f24334c4d86)


### After
![ASCII Art]  (https://github.com/user-attachments/assets/2384a75e-33d5-45d5-8105-c9799671257c)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Acknowledgements

- [Pillow](https://python-pillow.org/)
- [Tkinter](https://wiki.python.org/moin/TkInter)

---

=
