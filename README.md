# TorchBearer website

The public one-page site for TorchBearer. It links to the product app.

- **Live:** see the Amplify app `torchbearer-site` (AWS account 744438387719, us-east-1).
- **Edit:** change `index.html` and push to `main`. Amplify redeploys in about a minute.
- **Preview locally:** open `index.html` in a browser.
- **Hosting:** AWS Amplify Hosting, static, no build step (`amplify.yml`). Uses Amplify's free `amplifyapp.com` address; a custom domain (Route 53) can be added later in Amplify → Custom domains without changing anything here.
- **App link:** the product runs separately (Amplify app `torchbearer`, branch `aws`) and stays password protected.
