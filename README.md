# Single page resume
My JAMstack based one page resume

# Getting started

Below are the steps to get your single page resume.

- Clone the repo
- Change the data/resume.json file with your details
- Get your profile photo rename it to profile.png and place at [/static/assets/images](/static/assets/images)
- Modify config.toml with your details. Enable or disable of sections can also be done there.
- Test by running `hugo serve -D` command from the root folder.

## Hosting

### In free GitHub pages
- Use the .github/workflows folder to do CI&CD
- Change the baseurl to suit to your GitHub pages url

### Anywhere else
- Run `hugo -D` to build the site
- It will publish the site to /public folder
- Upload the /public folder to your hosting space

# Environment

- [Hugo](https://gohugo.io/getting-started/quick-start/ )
