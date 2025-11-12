# Psychedelic Advent Calendar

A responsive, touch-friendly psychedelic advent calendar web app with 24 doors that unlock based on date. Each door reveals a link to inspiring psychedelic art, music, or visual content.

## Features

- **24 Doors**: One for each day of December (1-24)
- **Date-based Unlocking**: Doors only open on or after their designated date
- **Psychedelic Design**: Animated gradients, kaleidoscope effects, and smooth animations
- **Responsive**: Works seamlessly on desktop, tablet, and mobile
- **Touch Optimized**: Smooth interactions with proper touch targets
- **Testing Support**: Use `?testDate=YYYY-MM-DD` URL parameter to test with different dates

## Usage

Open `index.html` in a modern web browser. The calendar will automatically check the current date and enable doors accordingly.

### Testing Different Dates

To test the calendar with different dates, add a URL parameter:

- `index.html?testDate=2024-12-10` - Opens doors 1-10
- `index.html?testDate=2024-12-24` - Opens all doors
- `index.html?testDate=2024-11-30` - All doors disabled (before December)

## Customizing Content

Edit the `contents` array in `index.html` to customize the links behind each door. Each entry should follow this format:

```javascript
{ title: "Link Title", url: "https://example.com" }
```

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Requires CSS Grid and LocalStorage support

## Deployment

This is a static site that can be hosted on GitHub Pages, Netlify, Vercel, or any static hosting service. Simply upload the `index.html` file.


