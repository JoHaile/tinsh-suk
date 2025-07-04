# የሱቅ አስተዳደር ስርዓት (Shop Management System)

This is a simple shop management system built entirely in a single `index.html` file. The application allows you to:

- Record daily sales and view current day's sales summary
- Add and manage quick sale items (predefined items)
- Adjust prices for quick sale items
- Retrieve and view historical sales data by date
- All data is stored locally in your browser (no server required)

## Why is everything in one file?

**The reason for building this as a single `index.html` file is because some mobile phone browsers do not work properly when CSS and JavaScript files are separated.** By keeping all the HTML, CSS, and JavaScript in one file, the application works reliably on a wider range of devices, especially on mobile browsers that have issues loading external resources.

# How to Use

1. Open the `index.html` file in your browser (desktop or mobile).
2. Use the interface to add quick sale items, record sales, and view sales data.
3. All your data is saved in your browser's local storage.
4. Performs Better Without translating the page contents written in Amharic that includes the dates and that causes a problem in month translation.

## Features

- **Add Quick Sale Items:** Easily add frequently sold items for fast access.
- **Record Sales:** Log sales for any item, including quick sale items.
- **View Today's Sales:** See a summary of items sold and total revenue for the current day.
- **View Historical Data:** Select a date to view past sales records.
- **Mobile Friendly:** The layout and design are optimized for both desktop and mobile devices.

## Technology Used

- HTML5
- CSS3 (with [TailwindCSS CDN](https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css))
- JavaScript (all logic is in the same file)

## License

This project is open source and free to use.
