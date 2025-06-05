# 📖 Bible Verse Finder

This is a simple web application that allows you to easily find and display Bible verses. You can either look up specific verses by reference or browse chapters by selecting a testament, book, and chapter.

## Features

- **Direct Verse Lookup:** Enter a Bible reference (e.g., `John 3:16`, `Psalm 23`, `Genesis 1:1-5`) to instantly retrieve the corresponding verse(s).
- **Browse by Chapter:** Select a testament (Old or New), then a book, and finally a chapter to view its entire content.
- **User-Friendly Interface:** Built with Tailwind CSS for a clean, responsive, and intuitive design.
- **Dynamic Content Loading:** Fetches verse data from an external API (`bible-api.com`) to provide accurate and up-to-date results.
- **Loading Indicator & Error Handling:** Provides visual feedback during data fetching and informs the user of any issues.

## How to Use

1.  **Open `index.html`** in your web browser.

2.  **To look up a specific verse:**

    - Type your desired Bible reference into the input field (e.g., "Matthew 5:3-12").
    - Click the "**Get Verse**" button or press `Enter`.

3.  **To browse a chapter:**
    - Select "New Testament" or "Old Testament" from the first dropdown.
    - Choose a "Book" from the second dropdown.
    - Select a "Chapter" from the third dropdown.
    - Click the "**Browse Chapter**" button.

The fetched verse(s) or chapter content will be displayed in the designated area below the input fields.

## Technologies Used

- **HTML:** For the basic structure of the web page.
- **CSS (Tailwind CSS):** For styling and responsive design.
- **JavaScript:** For all interactive functionality, including fetching data from the Bible API, populating dropdowns, and displaying verses.
- **Bible API (`bible-api.com`):** The external service used to retrieve Bible verse data.

## Local Development

To run this application locally:

1.  Save the provided HTML code as `index.html`.
2.  Open `index.html` in your web browser. No special server setup is required as it's a client-side only application.

---
