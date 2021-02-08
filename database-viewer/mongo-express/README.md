# mongo-express

Web-based MongoDB admin interface. For more information, see https://github.com/mongo-express/mongo-express

Recommended ENV variables should be set:

- ME_CONFIG_MONGODB_AUTH_DATABASE: Your mongodb database
- ME_CONFIG_MONGODB_ADMINUSERNAME: Mongodb admin username
- ME_CONFIG_MONGODB_ADMINPASSWORD: Mongodb admin password
- ME_CONFIG_MONGODB_SERVER: Server hostname (example: mongodb)
- ME_CONFIG_MONGODB_ENABLE_ADMIN: Recommended to true
- ME_CONFIG_SITE_BASEURL: Set to the same value as HTTP endpoint (Example: /mongodb/). Make sure to set the HTTP endpoint to the same value.
- ME_CONFIG_BASICAUTH_USERNAME: Set an HTTP basic username
- ME_CONFIG_BASICAUTH_PASSWORD: Set an HTTP basic username

