# Evan James Johnson Memorial Website

This is a memorial website dedicated to celebrating the life of Evan James Johnson (1997-2014). The website features photos, memories, news articles, and video content about Evan's life.

## Project Structure

```
website/
├── index.html          # Main website file
├── fonts/             # Self-hosted font files
│   ├── CormorantGaramond-Regular.woff2
│   ├── CormorantGaramond-Regular.woff
│   ├── CormorantGaramond-SemiBold.woff2
│   ├── CormorantGaramond-SemiBold.woff
│   ├── Inter-Light.woff2
│   ├── Inter-Light.woff
│   ├── Inter-Regular.woff2
│   ├── Inter-Regular.woff
│   ├── Inter-Medium.woff2
│   └── Inter-Medium.woff
├── images/            # Photo gallery images
│   ├── evan-1.jpeg through evan-90.jpg
│   └── evan-circle.png    # Header profile image
├── archives/          # Archived copies of news articles
│   ├── wildcattales-article.pdf
│   └── planocourier-article.pdf
├── video/            # Backup video files
│   └── evan-memorial.mp4
└── wildcattales-preview.jpg  # News article thumbnail
```

## External Dependencies

1. **Video Hosting**
   - Primary: Vimeo (video ID: 115229456)
   - Backup: Local MP4 file

2. **Form System**
   - Google Forms for memory submissions
   - Form ID: 1FAIpQLSfhGfkN3MwCgEP15nJuhHCzjAsf1ri5f9LhxFfnKwHCl1SZ6g

3. **Fonts**
   - Self-hosted fonts (no external dependencies)
   - Cormorant Garamond (Regular, SemiBold)
   - Inter (Light, Regular, Medium)

4. **External Links**
   - Wildcat Tales article
   - Plano Star Courier article
   - (Both articles archived locally as PDFs)

## Maintenance Notes

### Image Gallery
- 90 images in total (evan-1.jpeg through evan-90.jpg)
- Images are displayed in random order
- Supports both JPEG and PNG formats
- Includes fallback handling for missing images

### Video Player
- Primary source: Vimeo embed
- Automatic fallback to local MP4 if Vimeo is unavailable
- Video dimensions: 640x360

### Memory Submissions
- Uses Google Forms for collecting new memories
- Form height: 600px
- Embedded in responsive container

### Browser Compatibility
- Uses standard HTML5 features
- Responsive design for all screen sizes
- No external JavaScript libraries required

## Long-term Preservation

1. **Local Backups**
   - Keep copies of all images
   - Store PDF versions of news articles
   - Maintain local copy of the memorial video
   - Archive all submitted memories periodically

2. **Content Updates**
   - New memories are automatically added through Google Forms
   - News section can be updated by editing index.html
   - Photo gallery supports additional images by following the naming convention

3. **Technical Maintenance**
   - Check external links periodically
   - Verify Vimeo video availability
   - Monitor Google Forms functionality
   - Update SSL certificates if using HTTPS

## Contact Information

For technical support or content updates, please contact:
[Contact information to be added] 