# 3scale-content-caching-demo
Demo app to test the 3scale content caching policy
Making a call to static content returns the Cache-control: public header that allows Apicast to cache the content.


# Hello World API

# hello [/hello]

'Hello world' endpoint.


## hello [GET]
'Hello world' endpoint.
+ Parameters:
    - in: query
      name: hello
      schema:
      type: string
      description: Say hello to
    - in: query
      name: user_key
      schema:
      type: string
      description: Webhook for 3scale
