# AI Image Generator

A Streamlit-based web application that generates images using the Replicate API and the recraft-ai/recraft-v3 model. This application provides a user-friendly interface for AI image generation with various styles and size options.

## 🌟 Features

- 🎨 Multiple image generation styles
- 📐 Various image size options
- 🔑 Secure API key management
- 💾 Session-based image history
- 📱 Responsive design
- ⚡ Real-time generation
- 🔄 Progress tracking

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Replicate API key ([Get it here](https://replicate.com))

### Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd [your-repo-name]
```

2. Create and activate a virtual environment:
```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

### Usage

1. Run the Streamlit app:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided URL (typically `http://localhost:8501`)

3. Enter your Replicate API key in the sidebar

4. Start generating images!

## 📝 How to Use

1. **API Key Setup**
   - Enter your Replicate API key in the sidebar
   - The key is securely stored during your session

2. **Image Generation**
   - Write your prompt in the text area
   - Select a style from the dropdown menu
   - Choose desired image dimensions
   - Click "Generate Image"

3. **Available Styles**
   - any
   - realistic_image
   - digital_illustration
   - digital_illustration/pixel_art
   - digital_illustration/hand_drawn
   - And many more...

4. **Available Sizes**
   - 1024x1024
   - 1365x1024
   - 1024x1365
   - And various other dimensions...

## 🛠️ Technical Details

### Dependencies

- `streamlit`: Web application framework
- `replicate`: Replicate API client
- `Pillow`: Image processing
- `requests`: HTTP requests
- `python-dotenv`: Environment variable management

### File Structure

```
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
└── README.md          # Documentation
```

## ⚠️ Important Notes

- Keep your API key secure and never commit it to version control
- Image generation may take a few moments depending on server load
- Generated images are stored only during the current session

## 🤝 Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [Replicate](https://replicate.com) for the image generation API
- [Streamlit](https://streamlit.io) for the web app framework
- [recraft-ai](https://replicate.com/recraft-ai/recraft-v3) for the image generation model

## 📞 Support

If you encounter any problems or have suggestions, please open an issue in the repository.
