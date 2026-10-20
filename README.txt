Pokegrand Exchange site

1. Open config.js and set the shop inbox:
   window.POKEGRAND_EMAIL = "shop@email.com";
   Leave the quotes. Save the file.

2. Upload every file in this folder to a public GitHub repository, including the assets folder, config.js, and .nojekyll.
   index.html has to sit at the top of the repo, not inside another folder.

3. In the repo: Settings, Pages, Source: Deploy from a branch.
   Branch: main, folder: / (root). Save.

The site address will look like https://USERNAME.github.io/REPO-NAME/

Until config.js has an email, the forms will say the shop inbox is not connected.
Forms send from the page. Messages arrive from HDMN Secure Mail.
Free GitHub Pages only works on a public repository.
