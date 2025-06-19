# Journalist Blog Website

A professional blog website built with Next.js, designed specifically for journalists who want to host their content for free on GitHub Pages.

## Features

- **Easy Content Management**: Simple admin interface to add and manage blog posts
- **Professional Design**: Clean, responsive design suitable for journalism
- **GitHub Pages Ready**: Static site generation for free hosting
- **SEO Optimized**: Built-in SEO best practices
- **Mobile Responsive**: Works perfectly on all devices
- **Fast Loading**: Optimized for performance

## Getting Started

### Option 1: Deploy to GitHub Pages

1. Fork this repository to your GitHub account
2. Go to your repository settings
3. Scroll down to "Pages" section
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Local Development

1. Clone the repository:
\`\`\`bash
git clone https://github.com/yourusername/journalist-blog.git
cd journalist-blog
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Customization

### 1. Update Your Information
- Edit the site title and description in each page component
- Replace placeholder images with your own photos
- Update contact information in the contact page
- Modify the about page with your biography and credentials

### 2. Add Your First Blog Post
- Visit `/admin` to access the blog management interface
- Click "New Post" to create your first article
- Fill in the title, excerpt, content, and category
- Click "Publish Post" to make it live

### 3. Customize Styling
- Colors and fonts can be modified in `tailwind.config.ts`
- Component styles are in the individual component files
- Global styles are in `app/globals.css`

## Deployment

### GitHub Pages Deployment

1. Build the static site:
\`\`\`bash
npm run build
\`\`\`

2. The built files will be in the `out` directory
3. Push your changes to GitHub
4. GitHub Pages will automatically deploy your site

### Manual Deployment

You can also deploy the `out` directory to any static hosting service like:
- Netlify
- Vercel
- AWS S3
- Any web hosting provider

## Content Management

### Adding Blog Posts
1. Go to `/admin` on your live site
2. Click "New Post"
3. Fill in all the required fields
4. Use Markdown formatting for rich text
5. Click "Publish Post"

### Managing Existing Posts
- View all posts in the admin dashboard
- Edit or delete posts as needed
- Posts are stored in the component state (for a production site, you'd want to use a CMS or database)

## SEO Features

- Automatic meta tags generation
- Structured data for articles
- Optimized images
- Fast loading times
- Mobile-friendly design

## Support

If you need help customizing your blog or have questions about deployment, feel free to:
- Open an issue on GitHub
- Check the Next.js documentation
- Review the Tailwind CSS documentation

## License

This project is open source and available under the MIT License.
