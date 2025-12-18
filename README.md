📰 Alagesan Tech Blog

A modern, responsive static tech blog built with HTML, CSS, and Vanilla JavaScript, focused on delivering curated technology news, AI insights, and industry updates with a clean UI and smooth user experience.

This project is designed to be lightweight, fast, and easily deployable on platforms like Netlify.

🚀 Features

📱 Fully Responsive UI (Desktop, Tablet, Mobile)

🎨 Modern design with animations & smooth transitions

🧠 Curated tech blog posts rendered dynamically

⭐ Featured article section

📩 Newsletter subscription UI (backend-ready)

🔝 Smooth scrolling & back-to-top button

⚡ Fast loading (no frameworks, no build step)

🛠️ Tech Stack

HTML5 – Semantic and accessible structure

CSS3 – Modern layouts, animations, responsive design

JavaScript (Vanilla) – Dynamic rendering & interactions

Font Awesome – Icons

Unsplash – High-quality images

No frameworks. No dependencies. Just clean code.

📂 Project Structure
blog/
├── index.html        # Main application file
├── README.md         # Project documentation
└── netlify/          # (Optional) Netlify Functions
    └── functions/
        └── subscribe.js


⚠️ The netlify/functions folder is optional and only required if backend features are enabled.

🧩 How It Works

Blog posts are stored as a JavaScript array

Cards are dynamically rendered on page load

Featured article is automatically selected

Newsletter form is backend-ready and can be connected later

All UI interactions are handled using Vanilla JavaScript

🌐 Deployment (Netlify)

This project is optimized for Netlify static hosting.

Netlify Settings:
Setting	Value
Build Command	(leave empty)
Publish Directory	/
Functions Directory	netlify/functions (only if used)

Ensure the main file is named index.html

🔌 Backend Integration (Optional)

The newsletter form is designed to support:

Netlify Functions

External Node.js API

EmailJS / Supabase (future upgrade)

Backend can be enabled later without changing UI code.

🧪 Local Development

Just open the file in a browser:

index.html


No server required.

📸 Screenshots

Add screenshots here for better presentation
Example:

/screenshots/home.png
/screenshots/mobile.png

📈 Future Improvements

Real database for newsletter subscribers

Admin dashboard for posts

SEO optimization (meta, OG tags)

Blog post filtering by category

CMS or Markdown-based posts

👨‍💻 Author

Alagesan
Full-Stack Developer | Tech Enthusiast

📍 Sanarpatti, Dindigul, India
📧 alagesanalagu178@gmail.com

📞 +91 79043 21890

📄 License

This project is open-source and available for learning and personal use.
