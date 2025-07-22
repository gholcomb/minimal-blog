# Minimal Blog

A simple, clean, and minimal blog built with vanilla HTML, CSS, and JavaScript. Perfect for personal blogging with admin controls and image support.

## 🎯 Two-Part System

### **Admin Panel (`admin.html`)**
- **Private access** - Only you use this
- **Write and edit posts** with rich text editor
- **Upload images/GIFs** with drag & drop
- **Manage all posts** - edit, delete, view
- **Save drafts** functionality
- **Post management** interface

### **Public Blog (`index.html`)**
- **Public access** - Anyone can view
- **Clean reading experience** - no writing forms
- **Individual post pages** with full content
- **Image support** - displays uploaded images
- **Responsive design** for all devices

## ✨ Features

### **For You (Admin)**
- ✍️ **Rich writing interface** with image upload
- 🖼️ **Drag & drop image/GIF upload**
- 📝 **Draft saving** - never lose your work
- ✏️ **Edit existing posts** easily
- 🗑️ **Delete posts** with confirmation
- 📊 **Post management** dashboard
- 🔗 **Quick view** of public posts

### **For Readers (Public)**
- 📖 **Clean reading experience**
- 🖼️ **Image and GIF support**
- 📱 **Mobile responsive**
- 🔍 **Individual post pages**
- 📊 **Blog statistics**
- ⚡ **Fast loading** - no server required

## 🖼️ Image Support

- **Upload images/GIFs** in the admin panel
- **Drag & drop** or click to upload
- **Supports**: JPG, PNG, GIF, WebP
- **Automatic display** in blog posts
- **Responsive images** that scale properly

## 📁 File Structure

```
minimal-blog/
├── index.html     # Public blog (read-only)
├── admin.html     # Admin panel (write/edit)
└── README.md      # This file
```

## 🚀 How to Use

### **For Writing (Admin)**
1. Open `admin.html` in your browser
2. Write your post title and content
3. Upload images by dragging & dropping or clicking
4. Click "Publish Post" to publish
5. Use "Save Draft" to save work in progress

### **For Reading (Public)**
1. Open `index.html` in your browser
2. Browse all published posts
3. Click post titles to read full articles
4. Images will display automatically in posts

## 🔒 Security Note

This is a client-side only blog. For production use, consider:
- **Password protecting** the admin panel
- **Server-side storage** for posts
- **Image hosting** on a CDN
- **Backup system** for your content

## 🎨 Customization

You can easily customize:
- **Colors** by editing CSS variables
- **Fonts** by changing font-family properties
- **Layout** by modifying container widths
- **Styling** by updating CSS classes

## 🌐 Deployment

Since this is a static site, you can deploy it on:
- **GitHub Pages** (free)
- **Netlify** (free tier)
- **Vercel** (free tier)
- **Any web hosting** service

## 📱 Browser Compatibility

Works in all modern browsers that support:
- ES6 Classes
- localStorage
- FileReader API
- CSS Grid & Flexbox

## 📝 License

This is a template - feel free to use and modify as you like! 