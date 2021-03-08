# A WOMAN IS A SCHOOL




# Development

### Setup

Requires `ruby` with `rubygems`, `node` and `yarn`

1. `bundle install`
1. `yarn install`


### Local Development

This needs to be better, but works for now.

1. `yarn run dev-webpack` in one terminal window
1. `yarn run dev-jekyll` in another


### Deploy

Set up your favourite static site hosting, I used to run S3 but now I'm all Firebase Hosting.

So now it’s set up for firebase, just run `yarn run deploy-stage` or `yarn run deploy-production`.
