# NN Instagram Carousel

A beautiful, customizable Instagram carousel section for Shopify themes.

## Features

- 🎨 **Fully Customizable** - Control every aspect through Shopify theme editor
- 📱 **Responsive** - Perfect on mobile and desktop
- 🖼️ **Multiple Layouts** - Grid, carousel, or masonry layouts
- ⚡ **Performance Optimized** - Pure Liquid & CSS, minimal JavaScript
- 🎯 **Instagram Integration** - Direct linking to Instagram posts
- 🔧 **Block-based** - Modular design with reusable blocks

## Instagram-Specific Files

### Blocks
- `blocks/instagram-post-card.liquid` - Main card container
- `blocks/instagram-post-image.liquid` - Image/video display with overlay
- `blocks/instagram-post-caption.liquid` - Caption with line clamping
- `blocks/instagram-post-meta.liquid` - Likes and comments display

### Sections
- `sections/instagram-carousel.liquid` - Main carousel section

## Installation

1. Download the files listed above
2. Upload to your Shopify theme:
   - Blocks → `blocks/` folder
   - Section → `sections/` folder
3. Add the section to your theme in the theme editor

## Configuration

### Section Settings
- **Layout Type**: Grid, Carousel, or Masonry
- **Post Limit**: How many posts to display
- **Columns**: Grid columns (desktop/mobile)
- **Gap**: Spacing between cards
- **Navigation**: Arrows, dots, or counter

### Card Settings
- **Alignment**: Left, center, or right
- **Gap**: Internal spacing
- **Border Radius**: Corner rounding

### Image Settings
- **Aspect Ratio**: 1:1, 4:5, 3:4, 2:3, or adapt
- **Overlay**: Toggle Instagram icon overlay on hover
- **Overlay Opacity**: Control darkness of overlay

### Caption Settings
- **Max Lines**: Limit caption length (line clamping)
- **Font Size**: Control text size

### Meta Settings
- **Show Likes/Comments**: Toggle visibility
- **Icon Style**: Filled, Outline, Rounded, or Emoji

## Requirements

- Shopify theme
- Instagram metaobject with structure:
  - `Username` (single line text)
  - `posts` (list of instagram-post metaobjects)

## Metaobject Structure

### instagram-list
- `Username` - Your Instagram handle
- `posts` - References to instagram-post entries

### instagram-post
- `images` - Media files (images/videos)
- `caption` - Post caption text
- `likes` - Number of likes
- `comments` - Number of comments

## Version

Current: 1.0.0

## License

MIT

## Support

For issues or questions, please open an issue on GitHub.
