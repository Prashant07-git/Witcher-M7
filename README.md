Witcher M7 – PC Build Log

This is a simple static website to showcase the Witcher M7 PC build.

Viewing it locally

If you just want to see how the site looks:

Open the index.html file in your browser
That’s it — no setup or installation needed
Deploying on AWS Amplify

To put your site online:

Create a new repository on GitHub
Upload (push) all project files to that repository
Go to AWS Amplify
Click on Deploy an app
Connect your GitHub account and select your repository
Keep the default settings (since this is a static site, no build step is required)
Deploy

Once done, Amplify will give you a live URL for your site

Adding images

Place your PC build images inside the images folder with these names:

pc-1.jpg
pc-2.jpg
pc-3.jpg
pc-4.jpg
pc-5.jpg
Recommended image tips:
Keep width around 1600px for good quality
Use JPG or WebP format
Try to keep each image under 350 KB
Compress images using tools like TinyPNG or Squoosh before uploading
Telegram contact form setup

The contact form works through a Cloudflare Worker:

