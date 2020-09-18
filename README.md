<div id="top" />
<link rel="shortcut icon" type="image/x-icon" href="noobaa_icon.png">
<img src="noobaa_logo.png" width="200" />

----

NooBaa is a highly customizable and dynamic data gateway for objects, providing data services such as caching, tiering, mirroring, dedup, encryption, compression,  over any storage resource including S3, GCS, Azure Blob, Filesystems, etc.

NooBaa simplifies data for admins by connecting to any of the storage silos from private or public clouds, and providing a single scalable data services, using the same S3 API and management tools. NooBaa allows full control over data placement, letting you place data based on security, strategy and cost considerations, per user/application.

----

## Getting started

- [noobaa cli](noobaa-cli.md) 
- [noobaa install](noobaa-install.md)
- [noobaa status](noobaa-status.md)
- [noobaa verify](noobaa-verify.md)

## User guides

- [Getting help]()
- [Setup backing stores]()
- [Setup bucket classes]()
- [Setup routes, SSL, certificates, etc]()
- [Running on minikube]()

## Documentation

- [NooBaa CRD](noobaa-crd.md) - The basic CRD to deploy a NooBaa system.
- [BackingStore CRD](noobaa-backing-store.md) - Connection to cloud or local storage to use in policies.
- [BucketClass CRD](noobaa-bucket-class.md)  - Policies applied to a class of buckets.
- [OBC Provisioner](noobaa-obc.md) - Method to claim a new/existing bucket.

## Community

- [Email group noobaa@googlegroups.com](https://groups.google.com/g/noobaa)
- [Slack channel](https://www.noobaa.io/community)

## Developers

- [How to Contribute](/CONTRIBUTING.md)  
- [Developers Guide](https://github.com/noobaa/noobaa-core/wiki/Developers-Guide) 

## License

Apache License 2.0, see [LICENSE](/LICENSE)
