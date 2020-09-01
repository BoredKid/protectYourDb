# protectYourDb
List of action that can be taken to protect the db (based on a MongoDB)

- Set up firewall
- Restrict IP that can access to the db (bindIp) and avoid having to much IP allowed to access. Avoid using bindIpAll
- Change port from the default port. For instance, for mongo, use another port than 27017
- Do not use the production database in dev mode or test mode
- Disable http interface. For Mongo, by default, we can use the 28017 port with http. We can disable it with "nohttpinterface = true"
- Disable rest interface. It should be already off by default but if it isn't "rest = false"

*The list will be updated progressively*


## References
[https://scalegrid.io/blog/10-tips-to-improve-your-mongodb-security/]
[https://docs.mongodb.com/manual/security/]
