# Cloudform - Survey Builder

A modern survey builder tool for creating and managing customer surveys. Built with React and Tailwind CSS in a single HTML file for easy deployment.

## 🚀 Features

- **Visual Survey Builder**: Create surveys with an intuitive drag-and-drop interface
- **Multiple Question Types**: Support for text, multiple choice, rating scales, and more
- **Real-time Preview**: See your survey as you build it
- **Export Options**: Export surveys in various formats
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Cloudflare Branding**: Styled to match Cloudflare design system

## 🛠️ Tech Stack

- **React** - UI framework (via CDN)
- **Tailwind CSS** - Styling (via CDN)
- **Babel** - JSX transformation (via CDN)
- **Pure HTML** - Single-file deployment

## 📦 Installation & Deployment

This is a single HTML file that requires no build process:

### Local Development
```bash
# Simply open the file in your browser
open index.html
```

### Cloudflare Pages (Recommended)
1. Push to GitHub
2. Connect to Cloudflare Pages
3. No build configuration needed
4. Automatic deployments on push

### Other Platforms
Upload `index.html` to any static hosting:
- Netlify
- Vercel
- GitHub Pages
- Amazon S3
- Any web server

## 🎨 Features

### Survey Question Types
- Text input
- Multiple choice
- Checkboxes
- Rating scales
- Dropdown menus
- Date/time pickers

### Survey Management
- Create new surveys
- Edit existing surveys
- Preview surveys
- Export/share surveys
- Response tracking (future feature)

## 🚢 Usage

1. **Create a Survey**: Click "New Survey" to start
2. **Add Questions**: Choose from available question types
3. **Customize**: Edit question text, options, and settings
4. **Preview**: See how your survey will look to respondents
5. **Export**: Download or share your survey

## 🎨 Customization

All code is in `index.html`. Key areas to customize:

- **Branding**: Update colors and logos in the style section
- **Question Types**: Add new types in the React components
- **Export Formats**: Modify export functionality
- **Validation**: Add custom validation rules

## 📊 Survey Data

Surveys are stored in browser localStorage by default. For production use, consider:
- Cloudflare Workers/KV for backend storage
- Database integration
- API endpoints for survey management

## 🔒 Privacy

All survey data is stored locally in the browser. No data is sent to external servers unless you add that functionality.

## 📄 License

MIT
