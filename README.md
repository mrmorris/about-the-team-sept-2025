# About Our Team - September 2025

A beautiful, responsive team landing page that showcases our team members and their individual profiles.

## 🌟 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Team Landing Page**: Clean grid layout showcasing all team members
- **Individual Profiles**: Detailed pages for each team member with:
  - Personal information and background
  - Skills and expertise
  - Current projects
  - Fun facts and personal interests
- **Smooth Navigation**: Easy navigation between landing page and individual profiles
- **Modern Styling**: Professional gradient design with hover effects

## 🚀 How to View

### Option 1: Local HTTP Server (Recommended)
```bash
# Navigate to the project directory
cd about-the-team-sept-2025

# Start a simple HTTP server
python3 -m http.server 8000

# Open your browser and go to:
# http://localhost:8000
```

### Option 2: Direct File Access
Simply open `index.html` in your web browser by double-clicking it or dragging it into a browser window.

## 📁 Project Structure

```
about-the-team-sept-2025/
├── index.html          # Main landing page
├── styles.css          # CSS styling for all pages
├── profiles/           # Individual team member profiles
│   ├── john-doe.html
│   ├── jane-smith.html
│   ├── mike-brown.html
│   └── sarah-wilson.html
└── README.md
```

## 👥 Current Team Members

- **John Doe** - Software Engineer
- **Jane Smith** - UX Designer  
- **Mike Brown** - Project Manager
- **Sarah Wilson** - Data Scientist

## 🎨 Design Features

- Gradient header with team branding
- Card-based layout for team members
- Color-coded avatar initials
- Hover effects and smooth transitions
- Consistent typography and spacing
- Mobile-first responsive design

## 🛠️ Adding New Team Members

To add a new team member:

1. **Update `index.html`**: Add a new team member card in the `.team-grid` section
2. **Create Profile Page**: Create a new HTML file in the `profiles/` directory
3. **Update Links**: Ensure the profile link in `index.html` matches the new file name

Follow the existing structure and styling for consistency.