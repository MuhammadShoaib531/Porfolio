# Project Images

This folder contains the images for your portfolio projects.

## How to Add Your Project Images

1. Add your project images to this folder with the following names:
   - `chatbot-project.jpg` - For the AI Chatbot Platform project
   - `computer-vision-project.jpg` - For the Computer Vision System project  
   - `stock-predictor-project.jpg` - For the Stock Price Predictor project
   - `medical-ai-project.jpg` - For the Medical Image Analysis project

2. **Image Requirements:**
   - Format: JPG, PNG, or WebP
   - Recommended size: 400x300 pixels or larger
   - Aspect ratio: 4:3 or 16:9 works best
   - File size: Keep under 1MB for faster loading

3. **Image Tips:**
   - Use high-quality screenshots of your project interfaces
   - For AI/ML projects, consider using charts, dashboards, or results visualizations
   - Make sure images are clear and professional-looking
   - Consider adding a subtle overlay or border if needed

## Fallback Behavior

If an image file is missing, the website will show a purple gradient background with the project icon. The website will still function normally.

## Adding More Projects

To add more projects:

1. Add the project HTML in `index.html` following the existing structure
2. Add the corresponding image to this folder
3. Update the image `src` attribute to match your image filename

## Example Project Card HTML Structure

```html
<div class="project-card">
    <div class="project-image">
        <img src="assets/images/your-project-name.jpg" alt="Your Project Name" class="project-img">
        <div class="project-overlay">
            <i class="fas fa-your-icon"></i>
        </div>
    </div>
    <div class="project-content">
        <!-- Project details -->
    </div>
</div>
``` 