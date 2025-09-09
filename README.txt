my-static-website
-----------------
Files inside:
  - index.html
  - about.html
  - style.css
  - script.js

How to preview locally:
  1. Unzip the archive (if zipped).
  2. Open index.html in your web browser (double-click).

Quick deploy (recommended for beginners):
  1. Create an S3 bucket in AWS (unique name).
  2. Disable "Block all public access" for that bucket.
  3. Upload these files to the bucket.
  4. Enable "Static website hosting" in the bucket properties and set index document to index.html.
  5. (Optional) Create a CloudFront distribution using the S3 website endpoint as origin to get HTTPS and global caching.

If you want CLI commands to deploy, follow the separate instructions provided by the assistant.
