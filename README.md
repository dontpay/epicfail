# epicfail

just replace in play-or-pay-1.0.0.js
  c = lockArticle(;
with 
  c = lockArticle2();
=> dontpay.js

Install Requestly extension in Chrome
Create new Redirect Rule
  Equals: https://smartwall.swisspay.ch/play-or-pay-1.0.0.js
  Destination: https://cdn.rawgit.com/dontpay/epicfail/master/dontpay.js
=> dontpay.rule
