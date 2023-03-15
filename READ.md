 ### Commands
- Default port is `3000`. To use a custom port(xxxx), pass variable in the command itself.
  `PORT=xxxx node server/server.js`
- Basic https authentication is added.
- Username is `admin`.
- If you want to enable http authentication, define password in the command itself.
 `mypassword=xxx node server/server.js`
- Suggested to keep password as alphanumeric only. (suggested to avoid special characters)