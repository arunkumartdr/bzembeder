# bzembeder

# Cross-origin resource sharing
Cross-origin resource sharing (CORS) issues may occur when you pass PDF content as a URL and the PDF Embed API needs to download the file from the provided location in order to render it. To avoid this situation, you can choose one of two methods:

Locate your webpage and file location URL on the same domain. Example: webpage: https://example.com/viewer/test.html; PDF location: https://example.com/resources/abc.pdf)

Enable CORS headers on the PDF resource to allow access from your webpage domain.
