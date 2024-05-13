
# PixelCipher - Image Steganography

PixelCipher is a Python application for hiding and extracting messages within images using steganography techniques. This program provides a user-friendly graphical interface built with Tkinter, making it accessible for users to encode and decode messages effortlessly.

## Features

- **Encode**: Embed a message into an image.
- **Decode**: Retrieve a hidden message from an encoded image.

## Requirements

- Python 3.x
- Pillow (PIL) library
- Tkinter library

## Installation

1. Clone the repository or download the source code.
2. Install the required libraries using pip:
    ```bash
    pip install Pillow
    ```
3. Run the application:
    ```bash
    python stegno.py
    ```

## Usage

1. Launch the application by executing the script `stegno.py`.
2. The main menu will be displayed, offering options to encode or decode a message.
3. **Encoding a Message**:
    - Click on the "Encode" button.
    - Select an image to serve as the cover.
    - Enter the message to be hidden.
    - Optionally, provide a password for additional security.
    - Click the "Encode" button to conceal the message within the image.
4. **Decoding a Message**:
    - Click on the "Decode" button.
    - Choose the image containing the hidden message.
    - Enter the password if the image was encoded with one.
    - Click the "Decode" button to reveal the hidden message.
  
## Sample Output 

<div style="display: flex; justify-content: center;">
    <img src="https://github.com/Priya-M25/Steganography-Project-for-Hiding-Text-in-Images/assets/97019927/09e75003-45ff-4a65-b5f1-3c494f7f1be2" alt="Screenshot 1" width="300"/>
    <img src="https://github.com/Priya-M25/Steganography-Project-for-Hiding-Text-in-Images/assets/97019927/0546b384-af42-4bdd-ae63-a85fdabe8c47" alt="Screenshot 2" width="300"/>
    <img src="https://github.com/Priya-M25/Steganography-Project-for-Hiding-Text-in-Images/assets/97019927/4c62d767-eac5-4e77-88c5-9e316ce969b2" alt="Screenshot 3" width="300"/>
</div>


## Contribution

Contributions are welcomed and encouraged! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

