

# AI-Based Art Style Transfer

## Overview

The AI-Based Art Style Transfer application leverages neural networks to apply the artistic style of one image (e.g., a famous painting) to another image (e.g., a photograph). This project demonstrates the power of machine learning in creating unique and visually appealing artwork by merging content and style from two different images.

## Features

- **Upload Images:** Users can upload a content image and a style image.
- **Style Transfer:** The application applies the style of the uploaded style image to the content image using a neural style transfer model.
- **View Stylized Image:** Users can view and download the resulting stylized image.

## Requirements

- Python 3.8 or later
- TensorFlow
- Flask
- OpenCV
- NumPy
- Matplotlib
- Pillow

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Neural-Style-Transfer.git
   cd Neural-Style-Transfer
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Flask application:**
   ```bash
   python app.py
   ```

2. **Open your web browser and navigate to:**
   ```
   http://127.0.0.1:5000/
   ```

3. **Upload a content image and a style image:**
   - Click "Choose File" for both the content and style images.
   - Click "Upload and Transfer" to apply the style transfer.

4. **View and download the stylized image:**
   - The resulting stylized image will be displayed on the page.
   - Right-click the image to download it.

## Directory Structure

```
Neural-Style-Transfer/
├── static/
│   └── uploads/          # For user-uploaded images
├── templates/
│   └── index.html        # HTML template for the web interface
├── app.py                # Main Flask application
├── style_transfer.py     # Style transfer logic
├── requirements.txt      # List of dependencies
└── README.md             # Project overview and instructions
```

## Example

Here's an example of how the application works:

1. **Content Image:**
   ![Content Image](static/uploads/content_image_example.jpg)

2. **Style Image:**
   ![Style Image](static/uploads/style_image_example.jpg)

3. **Stylized Image:**
   ![Stylized Image](static/uploads/stylized_image_example.jpg)

## Deployment

To deploy this application, consider using a cloud platform like Heroku, AWS, or Google Cloud. For a quick deployment on Heroku:

1. **Create a `Procfile`:**
   ```plaintext
   web: python app.py
   ```

2. **Deploy to Heroku:**
   ```bash
   heroku login
   heroku create
   git add .
   git commit -m "Deploy to Heroku"
   git push heroku master
   ```

## Contributing

Feel free to fork this repository, make enhancements, and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



