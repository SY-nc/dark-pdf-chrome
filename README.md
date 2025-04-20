# dark-pdf-chrome
Chrome extension to view PDF files in dark mode

Credits: [u/polysoma on r/chrome](https://www.reddit.com/r/chrome/comments/e3txhi/comment/fem1cto/) 

### Instructions:
Install extension:
- Chrome settings -> Extensions -> Load unpacked -> browse to cloned directory

\
To keep light mode as default:
- Open any pdf (should open in dark mode by default)
- Right click the extension icon -> 'this can read and change data' -> select 'when you click the extension'
- Accept tab reload prompt 

\
To extend color inversion to a website of your choice:
- add URL wildcard in manifest.json ('matches' field in 'content_scripts')

\
**NOTE**: Before adding URLs, consider previewing the color inversion accuracy:
- (on your URL) Open chrome console (right click -> inspect)
- Enter script from dark-mode-pdf.js in console