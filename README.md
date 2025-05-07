# DuckDuckGo Search Webpage with Proxy Fallback

## Description

This is a simple, client-side webpage that lets you search DuckDuckGo and view search results without running into browser CORS (Cross-Origin Resource Sharing) restrictions.  

It works by fetching DuckDuckGo’s HTML search results through multiple public proxy servers that add necessary CORS headers. When a proxy fails or is unavailable, it automatically tries the next one until it gets a successful response.

Additionally, the webpage fixes DuckDuckGo’s redirect links so clicking on a result takes you directly to the target website.

This project uses only HTML, CSS, and JavaScript — no backend server needed.

---

## Features

- Search DuckDuckGo directly from your browser.  
- Automatically tries multiple public CORS proxies to improve reliability.  
- Displays search result titles and snippets clearly.  
- Clicking result titles leads you straight to the actual destination (skipping DuckDuckGo redirects).  
- Simple and clean user interface designed for ease of use.  

---

## How to Use

1. Open the `index.html` file in a modern web browser (Chrome, Firefox, Edge, etc.).  
2. Type your search term into the input box.  
3. Press the **Search** button or hit Enter.  
4. Wait a moment while the app tries to fetch results via public proxies.  
5. View the list of results. Click titles to visit websites directly.

---

## Notes and Limitations

- The app depends on free public proxy services to bypass CORS restrictions. These proxies may sometimes be slow, limited, or temporarily unavailable.  
- If all proxies fail, you will see an error message asking you to try again later.  
- This app is recommended for lightweight or educational use rather than heavy production workloads.  
- No server setup or installation required — just open the HTML file locally.

---

## License

This project is open source and free to use. Feel free to modify and share!

---

## Acknowledgements

- DuckDuckGo for their HTML search endpoint and instant answers.  
- Public proxy services: [AllOrigins](https://allorigins.win), [ThingProxy](https://thingproxy.freeboard.io), [CorsProxy.io](https://corsproxy.io) for enabling browser access to cross-origin content.
