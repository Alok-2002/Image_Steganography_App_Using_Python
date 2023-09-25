# Image Steganography App Using Python

![GitHub last commit](https://img.shields.io/github/last-commit/alok-2002/Image_Steganography_App_Using_Python)
![GitHub stars](https://img.shields.io/github/stars/alok-2002/Image_Steganography_App_Using_Python)
![GitHub repo size](https://img.shields.io/github/repo-size/alok-2002/Image_Steganography_App_Using_Python)


![image](https://github.com/Alok-2002/Image_Steganography_App_Using_Python/assets/93814546/31f0b3b5-830f-4f49-a32e-591889840123)


## Introduction

Welcome to the Image Steganography App, a project developed by [Alok Sharma](https://github.com/alok-2002). This app allows you to hide confidential text messages within images using the concept of steganography. Steganography is the art of hiding information within another seemingly innocuous medium, such as an image.

In this project, I utilized the power of Python and the `tkinter` library for creating the graphical user interface (GUI), and the `stegano` library for the steganography functionality. The app provides a user-friendly interface to encode text messages into images and decode hidden messages from images.

## Features

- Encode a text message into an image.
- Decode a hidden message from an image.
- Preview images before and after encoding/decoding.
- User-friendly GUI built with `tkinter`.
- Seamless integration with the `stegano` library for steganography operations.

## Prerequisites

To run this app on your local machine, you'll need the following:

- Python 3.x
- The `tkinter` library (usually included with Python installations)
- The `stegano` library, which you can install using:
  ```
  pip install tkinter stegano
  ```

## How to Use

1. Clone this repository to your local machine.
2. Make sure you have Python and the required libraries installed.
3. Run the `ImageCloak.py` script:
   ```
   python ImageCloak.py
   ```
4. The app window will open, providing options to encode and decode messages.
5. To encode a message:
   - Click on the "Open Image" button.
   - Select the target image and provide the message you want to hide.
   - Click "Save" to generate the encoded image.
6. To decode a message:
   - Click on the "Open Image" button.
   - Select the image containing the hidden message.
   - Click "Show Data" to reveal the hidden message.

## Screenshots

![image](https://github.com/Alok-2002/Image_Steganography_App_Using_Python/assets/93814546/989d4447-ec4b-43d5-9322-bd599cbfc6f9)
_Main window of the Image Steganography App._

![image](https://github.com/Alok-2002/Image_Steganography_App_Using_Python/assets/93814546/dc60f4d2-4635-4d12-a378-79e6a564153b)
_Encoding a message into an image._

![image](https://github.com/Alok-2002/Image_Steganography_App_Using_Python/assets/93814546/ea90a532-9754-4153-a415-46d9d16381e0)
_Decoding a hidden message from an image._

## Future Enhancements

This project serves as a foundation for further improvements. Here are some ideas to enhance the app:

- Implement password protection for encoded messages.
- Support for different file formats, not just images.
- Integration with cloud storage for sharing encoded images.
- Batch processing for encoding/decoding multiple images.

## Contributions

Contributions to this project are welcome! If you have any ideas for improvements or new features, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore and use this Image Steganography App for your own purposes. If you have any questions or suggestions, please don't hesitate to contact me at [sharmaalok02gwl@gmail.com](mailto:sharmaalok02gwl@gmail.com). Happy coding!
