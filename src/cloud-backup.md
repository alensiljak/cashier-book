# Cloud Backup

On this screen you can backup and restore most, if not all, the data and settings used by Cashier. The storage access is expected to be a WebDAV server.

Cashier will used the configured Server URL as the root folder to use. 

## Setting up a server

A recommended solution is to use RClone, and this will be used in the description below. You can, however, use any WebDAV server you prefer.

To run rclone as the WebDAV server, execute:

```
rclone serve webdav <source> --allow-origin "*"
```

where the `<source>` marks any source storage provider supported by RClone. This may be a local storage, or any cloud storage provider. This makes it a convenient proxy to a number of cloud storage providers out there.

This also removes any need for Cashier to handle access credentials to your cloud provider as you can set that up with RClone separately.
