# This repo is modified from oni-web repo, some configuration in previous repo is not updated.
https://github.com/oni-web/web-frontend
https://github.com/oni-web/oni-web

# Deploy to netlify

### Build settings in netlify

Build command:
    CI=false npm run build && cp _redirects build/


### Useful FAQ
1. [“Treating warnings as errors because of process.env.CI = true”](https://dev.to/kapi1/solved-treating-warnings-as-errors-because-of-process-env-ci-true-bk5)
2. https://www.google.com/search?q=A+%22_redirects%22+file+is+present+in+the+repository+but+is+missing+in+the+publish+directory+%22build%22.&rlz=1C5GCEM_enUS1009US1011&sourceid=chrome&ie=UTF-8
3. [Some other ways to set proxy](https://create-react-app.dev/docs/proxying-api-requests-in-development/)
4. [_redirects file under the root directory](https://stackoverflow.com/questions/67986822/api-from-proxy-not-working-after-deploying-on-netlify)
5. 



