# Personal Website Flask App

A modern personal website built with Flask and Bootstrap 5.

## Features

- Responsive design
- Modern UI with animations
- Bootstrap 5 integration
- Font Awesome icons
- Hero section with dynamic background
- About and Contact sections
- Social media links

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
my-flask-app/
├── app.py
├── requirements.txt
├── static/
│   └── css/
│       └── style.css
└── templates/
    └── home.html
```

## Customization

- Edit `templates/home.html` to modify the content
- Update `static/css/style.css` to change the styling
- Add your social media links in the contact section
- Replace the hero background image by modifying the URL in `style.css`

## License

MIT License 