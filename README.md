## Day 25 Demo Application Built Using Tornado , MongoDB , AngularJS, and OpenShift

To deploy it on OpenShift

```
$ rhc create-app day25demo python-2.7 mongodb-2 --from-code https://github.com/shekhargulati/day25-tornado-demo-app.git
```


Via: https://blog.openshift.com/day-25-tornado-combining-tornado-mongodb-and-angularjs-to-build-an-app/

## Make sure to run this commands

$ virtualenv venv --python=python2.7
$ . venv/bin/activate
$ pip install tornado
$ pip install pymongo
