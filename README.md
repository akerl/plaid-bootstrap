plaid-bootstrap
==============

This repo simplifies Plaid authentication by providing a dummy web page for generating Plaid account connections.

The code originated from https://github.com/plaid/quickstart/tree/master/ruby 

```
git clone https://github.com/akerl/plaid-bootstrap
cd plaid-bootstrap
bundle
# Get your Plaid API creds from https://dashboard.plaid.com/account/keys
export PLAID_CLIENT_ID=
export PLAID_SECRET=
bundle exec ruby app.rb
# Go to http://localhost:4567
```
