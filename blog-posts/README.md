# Blog System

This directory contains the blog posts for Kevin Wang's portfolio website.

## Adding New Blog Posts

### Method 1: Edit blog.html directly

1. Open `blog.html` in the root directory
2. Add a new `<article>` element with the following structure:

```html
<article class="blog-post" id="post-unique-id" data-category="Category Name">
  <h2 class="blog-post-title">Your Blog Post Title</h2>
  <div class="blog-post-meta">
    <span><i class="fa fa-calendar"></i> Date</span>
    <span><i class="fa fa-user"></i> Kevin Wang</span>
    <span class="blog-post-category">Category Name</span>
  </div>
  <div class="blog-post-excerpt">
    <p>Brief excerpt of your blog post...</p>
  </div>
  <div class="blog-post-content">
    <p>Your full blog post content here...</p>
    
    <h3>Section Headers</h3>
    <p>Support for multiple sections...</p>
    
    <blockquote>
      "Quotes are supported with blockquote tags"
    </blockquote>
    
    <ul>
      <li>Lists are supported</li>
      <li>Both ordered and unordered</li>
    </ul>
    
    <pre><code>
    // Code blocks are supported
    function example() {
      return "Hello World";
    }
    </code></pre>
  </div>
  <a href="#" class="read-more-btn">
    <i class="fa fa-arrow-right"></i>
    Read Full Post
  </a>
</article>
```

3. Add the post to the recent posts sidebar by updating the `.recent-posts` section

### Method 2: Markdown Files (Future Enhancement)

For full markdown support, you would need to:

1. Create `.md` files in this directory
2. Add a JavaScript markdown parser to `blog.html`
3. Implement dynamic loading of markdown files

## Categories

Current supported categories:
- AI Research
- Computer Vision
- Academic Life
- Programming
- Research
- Conferences

## Features

- **Responsive Design**: Works on all device sizes
- **Search Functionality**: Real-time search through post content
- **Category Filtering**: Filter posts by category
- **Analytics Tracking**: Google Analytics integration
- **Code Highlighting**: Syntax highlighting for code blocks
- **Mobile-Friendly**: Optimized for mobile viewing

## Styling

The blog uses:
- Material Design components
- Teal color scheme matching the main portfolio
- Professional typography
- Hover effects and smooth transitions
- Responsive grid layout

## Analytics

The blog tracks:
- Blog post clicks
- Category filtering
- Search usage
- Read more button clicks

All analytics data is sent to Google Analytics (G-55V1E709SK). 