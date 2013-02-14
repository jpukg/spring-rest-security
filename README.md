spring-rest-security
====================

This project is an example to how authenticate a RESTfull api without to use sessions, dbsession or cookies. The process is 
very similar to the AWS (Amazon Web Services) but the intention is to turn in an Open Source Project to make authentications easy when need to use REST.

GOALS | STATUS:
- start a  project using spring 3 mvc [OK]
- configuring a http interceptor to all api request [OK]
- create the authentication logic layer
- add support to timed tokens
- add support to unique tokens(lifetime managed by redis.io)
- create the unit tests (POST,GET,DELETE,PUT)
- create a jar project library
- create a gitHub documentation
