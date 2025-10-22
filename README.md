# Amgen Stock Shares Outstanding Viewer

## Overview

This web application fetches and displays the number of common stock shares outstanding for Amgen (CIK 0000318154) from the U.S. Securities and Exchange Commission (SEC) data API.

The app dynamically updates the entity name, maximum, and minimum shares outstanding figures for fiscal years after 2020, based on available data.

## Features
- Mobile responsive and visually styled with Bootstrap 5
- Fetches data with a custom User-Agent as per SEC guidelines
- Supports specifying a different CIK via URL parameter (e.g., `?CIK=0001018724`)
- Graceful error handling
- Stores fetched data in local storage for potential future use

## Usage

Open the `index.html` file in a web browser. To view data for a different CIK, append `?CIK=XXXXXXXXXX` to the URL.

## Notes
- The application uses a proxy (AIPipe) to circumvent CORS issues when fetching data for CIKs other than Amgen.
- Make sure to serve this file via a web server or open directly from the filesystem.

## License

This project is licensed under the MIT License.

---

## License

MIT License

<Insert full MIT License text here, see below> 

## License Text

MIT License

Copyright (c) 2023

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.