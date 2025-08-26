# vCard Website

A simple personal contact website that serves a vCard file and displays contact information.

## Files

- `contact.vcf` - The vCard file containing contact information
- `index.html` - The main webpage displaying contact details
- `vercel.json` - Vercel deployment configuration
- `package.json` - Project metadata

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Login to Vercel:
   ```bash
   vercel login
   ```

3. Deploy:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Vercel will automatically deploy

### Option 3: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Drag and drop your project folder
4. Deploy

## Customization

1. Edit `contact.vcf` with your actual contact information
2. Update `index.html` with your name, title, and contact details
3. Customize the styling in the `<style>` section of `index.html`

## Usage

Once deployed, your vCard will be available at:
- `https://your-domain.vercel.app/contact.vcf` - Direct vCard download
- `https://your-domain.vercel.app/` - Contact webpage

## Features

- ✅ Responsive design
- ✅ Direct vCard download
- ✅ Clean, professional layout
- ✅ Mobile-friendly
- ✅ SEO optimized
