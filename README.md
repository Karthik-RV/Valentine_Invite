# Valentine's Day Website for Rose 🌹

A charming Valentine's Day proposal website with an interactive twist - the "No" button moves away when you try to click it!

## Features

✨ Beautiful, romantic design with floating hearts
💕 Interactive "No" button that escapes the cursor
🎉 Celebration animation when "Yes" is clicked
📱 Responsive and mobile-friendly
🌹 Custom design with rose-themed colors

## How It Works

The "No" button detects when the mouse cursor gets within 100 pixels and automatically moves to a random position, making it impossible to click. The only way to respond is by clicking "Yes"!

## Installation & Setup

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Step 1: Install Flask
```bash
pip install -r requirements.txt
```

Or manually:
```bash
pip install Flask
```

### Step 2: Run the Application
```bash
python app.py
```

### Step 3: Open in Browser
Once the server starts, open your web browser and go to:
```
http://localhost:5000
```

Or if accessing from another device on the same network:
```
http://YOUR_IP_ADDRESS:5000
```

## File Structure

```
valentine-website/
│
├── app.py                  # Flask application (main Python file)
├── requirements.txt        # Python dependencies
├── README.md              # This file
│
└── templates/
    └── valentine.html     # HTML template with CSS and JavaScript
```

## Customization

### Change the Name
Edit `templates/valentine.html` and find:
```html
<h1>Hey <span class="name">Rose</span>!</h1>
```
Replace "Rose" with any name you'd like.

### Adjust Colors
The color scheme uses CSS variables defined at the top of the `<style>` section:
```css
:root {
    --rose-red: #FF6B9D;
    --soft-pink: #FFC2D4;
    --cream: #FFF5F7;
    --deep-rose: #C73866;
}
```

### Change the Question
Find this line and modify the text:
```html
<p class="question">Will you be my Valentine?</p>
```

### Adjust Button Sensitivity
In the JavaScript, find this line to change how close the cursor needs to be:
```javascript
if (distance < 100) {  // Change 100 to any value
    moveButton();
}
```

## Troubleshooting

**Port already in use?**
Change the port in `app.py`:
```python
app.run(debug=True, host='0.0.0.0', port=5001)  # Use different port
```

**Flask not found?**
Make sure Flask is installed:
```bash
pip install Flask
```

## Technologies Used

- **Backend**: Python with Flask framework
- **Frontend**: HTML5, CSS3, JavaScript
- **Fonts**: Google Fonts (Pacifico, Quicksand)
- **Design**: Custom CSS animations and gradients

## License

Free to use for personal romantic purposes! 💕

---

Good luck with your Valentine's proposal! 🌹
"# Valentine_Invite" 
"# Valentine_Invite" 
"# Valentine_Invite" 
"# Val-Invite" 
