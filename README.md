Any files in the ./overview/articles directory will render at this path: https://staging.covid-watch.org/articles/index.html

LOCAL: localhost:3000/articles/index.html
STAGING: https://staging.covid-watch.org/articles/index.html
PRODUCTION: www.covid-watch.org/articles/index.html

The script to push to staging and production can be found at ./overview/scripts/build.sh

There are further instructions and commands commented at the top of build.sh.

To contribute to this repo, run the following commands to run locally:
1. git clone <repo URL>
2. navigate to /overview directory
3. npm install
4. npm run dev
5. in your browser go to URL: localhost:3000/articles/index.html

You may hit an error "Can't resolve '~/secret.json'".  If you do, create a file in the /overview directory called 'secret.json'.  Reach out to others involved with this project for the necessary credentials to paste there.