# Deployment Guide: Physical AI & Humanoid Robotics Book

## Deploying to Vercel

This guide will walk you through deploying your Physical AI & Humanoid Robotics book to Vercel.

### Prerequisites

- A GitHub account
- A Vercel account (free)
- The project repository (either your fork or original)

### Quick Deploy

The fastest way to deploy is using the Vercel button:

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/final-book&project-name=physical-ai-book&repo-name=physical-ai-book)

### Manual Deployment Steps

1. **Fork the Repository** (if not already done)
   - Go to your GitHub account
   - Fork the repository containing this project

2. **Sign Up/Log In to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up for a free account or log in if you already have one

3. **Create New Project**
   - Click "New Project" on your Vercel dashboard
   - Select "Import Git Repository"
   - Choose your forked repository from the list

4. **Configure Project Settings**
   - Project name: Choose any name (e.g., "physical-ai-book")
   - Framework preset: Docusaurus (should be auto-detected)
   - Root directory: Leave empty (or set to "my-website" if needed)
   - Build command: `npm run build`
   - Output directory: `build`
   - Development command: Leave empty

5. **Environment Variables** (Optional)
   - No environment variables are required for this project

6. **Deploy**
   - Click "Deploy" to start the deployment process
   - Vercel will automatically install dependencies and build your site
   - The process typically takes 1-3 minutes

7. **Access Your Deployed Site**
   - Once complete, you'll see a URL like `https://your-project-name.vercel.app`
   - Your site will be accessible at this URL

### Post-Deployment

1. **Custom Domain** (Optional)
   - In your Vercel dashboard, go to your project
   - Navigate to "Settings" → "Domains"
   - Add your custom domain if you have one

2. **Automatic Deployments**
   - Any changes pushed to your GitHub repository will automatically trigger a new deployment
   - This ensures your Vercel deployment stays up-to-date

### Configuration Files

The project includes these configuration files for Vercel deployment:

- `vercel.json`: Contains build configuration for Vercel
- `package.json`: Contains build scripts and dependencies
- `docusaurus.config.ts`: Contains site configuration

### Troubleshooting

**Build fails**:
- Check that all dependencies are properly listed in package.json
- Ensure the build command is set to `npm run build`
- Verify the output directory is set to `build`

**Site looks broken**:
- Check that the baseUrl in docusaurus.config.ts is set correctly
- For Vercel, baseUrl should typically be `/` (which it is in this project)

**Images or assets not loading**:
- Verify that static assets are in the `static` directory
- Check that paths in your markdown files are correct

### Environment-Specific Settings

For the Vercel deployment to work properly, the following settings in `docusaurus.config.ts` are important:

- `baseUrl`: Should be `/` for root deployment
- `url`: Should be your final domain (Vercel will handle this automatically)
- `organizationName` and `projectName`: Used for GitHub Pages, but won't affect Vercel deployment

### Updating Your Deployment

After the initial deployment:

1. Make changes to your local repository
2. Commit and push changes to GitHub
3. Vercel will automatically build and deploy the new version
4. You can monitor the deployment progress in your Vercel dashboard

### Best Practices

- Always test your changes locally with `npm run build && npm run serve` before pushing
- Use feature branches for major changes to avoid breaking your main deployment
- Monitor your deployment logs in the Vercel dashboard for any issues
- Set up custom domains for a more professional appearance

### Removing/Deleting Deployment

- Go to your Vercel dashboard
- Select the project you want to remove
- Go to Settings → Delete Project
- Confirm deletion (this will remove the live site)

Your Physical AI & Humanoid Robotics book is now ready for deployment on Vercel! The futuristic, premium UI with light/dark mode support will be available to your audience immediately after deployment.