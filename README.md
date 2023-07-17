# Invisibility Cloak using OpenCV 

This project implements an "invisibility cloak" effect using OpenCV in Python. The concept is inspired by the fictional invisibility cloak from the Harry Potter series.

The project works by capturing the background without any subject present, and then replacing the pixels corresponding to the subject with the background pixels in real-time, creating the illusion of invisibility.

## Requirements

To run this project, you need the following:

- Python 3.x
- OpenCV
- Numpy

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/taniishkaaa/invisibility-cloak.git
```

2. Change into the project directory:

```
cd invisibility-cloak
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Run the main invisibility cloak script:
   - Make sure you have a solid-colored cloth (preferably red) that you can use as the invisibility cloak.
   - Run the `invisibility-cloak.py` script:

     ```
     python invisibility-cloak.py
     ```

2. Once the script is running, it will open a window displaying the video feed from your camera.
   - Allow the camera to capture the background without any subject in the frame for 3 seconds(max).
   - Hold the cloth in front of you, covering yourself or any object you want to make invisible.
   - You should observe that the cloth-covered region will be replaced by the background, creating the illusion of invisibility.

4. To exit the program, press `q` or `Ctrl+C`.

## Customization

You can customize the project to fit your requirements:

- **Color Detection**: By default, the project uses red color detection to identify the invisibility cloak. You can modify the `lower` and `upper` values in the `invisibility-cloak.py` script to detect different colors.
- **Video Source**: The project uses the default camera as the video source. If you want to use a different video source, modify the `cap` variable in the `invisibility-cloak.py` script.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project is based on the wonderful tutorials and inspiration from the online community. Special thanks to the OpenCV community and the authors of the related tutorials and projects.
