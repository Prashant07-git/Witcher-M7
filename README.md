# Witcher M7

Static PC build log for the Witcher M7 setup.

## Local preview

Open `index.html` in a browser.

## AWS Amplify deployment

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. In AWS Amplify, choose **Deploy an app**.
4. Connect the GitHub repository.
5. Use the default static hosting settings. No build command is required.

## Images

Add optimized build photos to:

- `images/pc-1.jpg`
- `images/pc-2.jpg`
- `images/pc-3.jpg`
- `images/pc-4.jpg`
- `images/pc-5.jpg`

Recommended image sizes:

- Hero/gallery: 1600px wide, JPG/WebP, under 350 KB each if possible.
- Use TinyPNG, Squoosh, or ImageOptim before upload.

## Contact form options

The current form uses a `mailto:` fallback so it works on static hosting without a backend.

Free or low-cost upgrade paths:

- Formspree free tier for simple form submissions.
- Getform free tier for static sites.
- AWS Lambda + API Gateway + SES if you want everything inside AWS.
