bitstarter
==========

Address on Amazon:
ec2-54-213-62-166.us-west-2.compute.amazonaws.com

Address on Heroku:
Product: http://ajing-bitstarter-mooc-staging.herokuapp.com/
Staging: http://ajing-bitstarter-s-mooc.herokuapp.com/


Push to Production:
git push production-heroku master:master

Push to Staging:
git push staging-heroku master:master


Remember to kill the process after terminate "nodejs":
ps -e | grep -i node
kill -9 xxxx
