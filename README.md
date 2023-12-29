# Face Recognition System

## Introduction

This Python script implements a face recognition system using the `face_recognition` library. The system allows users to upload an image and authenticate themselves based on a pre-existing image associated with their email.

## Features

- Face recognition using the `face_recognition` library.
- Secure image upload and authentication process.
- Simple web interface for user interaction.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- face_recognition library (`pip install face_recognition`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/face-recognition-system.git
    cd face-recognition-system
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the script using Python:

    ```bash
    python face_recognition_script.py
    ```

2. Access the script through a web browser by navigating to `http://localhost:CGI_PORT` (replace `CGI_PORT` with the configured port).

3. Fill out the form with the required parameters:
   - `current_image`: The image to be authenticated.
   - `email`: The email associated with the pre-existing image.

4. Click the submit button, and the script will display an alert indicating whether the face was recognized.

## Directory Structure

- `uploads`: Directory to store uploaded images.
- `students`: Directory to store pre-existing user images.

## Contributing

Contributions are welcome! Please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
