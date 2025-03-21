# Zero Academic Page Starter Template

This is a quick start template for [Zero Academic Page](https://github.com/geekifan/zero-academic-page). It uses [Hugo modules](https://gohugo.io/hugo-modules/) feature to load the theme.

It comes with a basic theme structure and configuration. GitHub action has been set up to deploy the theme to a public GitHub page automatically. Also, there's a cron job to update the theme automatically everyday.

## Get started

1. Click *Use this template*, and create your repository as `<username>.github.io` on GitHub.
![Step 1](https://user-images.githubusercontent.com/5889006/156916624-20b2a784-f3a9-4718-aa5f-ce2a436b241f.png)

2. Once the repository is created, create a GitHub codespace associated with it.
![Create codespace](https://user-images.githubusercontent.com/5889006/156916672-43b7b6e9-4ffb-4704-b4ba-d5ca40ffcae7.png)

3. And voila! You're ready to go. The codespace has been configured with the latest version of Hugo extended, just run `hugo server` in the terminal and see your new site in action.

4. Check `hugo.toml` for the configuration file. You can edit them to suit your needs. Make sure to update the `baseurl` property in `hugo.toml` to your site's URL.

5. Open Settings -> Pages. Change the build branch from `main` to `gh-pages`.
![Build](https://github.com/namanh11611/hugo-theme-stack-starter/assets/16586200/12c763cd-bead-4923-b610-8788f388fcb5)

1. Once you're done editing the site, just commit it and push it. GitHub action will deploy the site automatically to GitHub page asociated with the repository.
![GitHub action](https://user-images.githubusercontent.com/5889006/156916881-90b8bb9b-1925-4e60-9d7a-8026cda729bf.png)

## Build and deploy locally

In case you don't want to use GitHub codespace, you can also run this template in your local machine. **First, you need to install Git, Go and Hugo extended locally.**.

1. Clone this repository to your local machine
```bash
git clone https://github.com/geekifan/zero-academic-page-starter && cd zero-academic-page-starter
```
2. Run `hugo server` in the terminal and see your new site in action.

3. Check `hugo.toml` for the configuration file. You can edit them to suit your needs. Make sure to update the `baseurl` property in `hugo.toml` to your site's URL.

4. Run `hugo build`.

5. Upload `public` directory to your server.

## Update theme manually

Run:

```bash
hugo mod get -u github.com/geekifan/zero-academic-page
hugo mod tidy
```