# ezplatform-bundle-skeleton

A skeleton to start a new eZ Platform Bundle project.

## Usage

Open a command console and execute:

```bash
$ compser create-project adamwojs/ezplatform-bundle-skeleton <bundle-name> 
```

This command requires you to have Composer installed globally, as explained
in the [installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

During the installation you will be asked for entering/confirmation of the following parameters used to generate bundle structure:

| Parameter        | Example                 | Description                                               |
|------------------|-------------------------|-----------------------------------------------------------|
| Package name     | `ezplatform-page-build` | Package name. By default same as project directory name   |
| Vendor name      | `ezsystems`             | Package vendor name.                                        |
| Bundle name      | `EzPlatformPageBuilder` | Bundle name __without__ `Bundle` suffix                   |
| Vendor namespace | `EzSystems`             | Bundle vendor namespace                                   |


The following environment variables are used to configure default parameters values:

* `VENDOR_NAME` - vendor name
* `VENDOR_NAMESPACE` - vendor namespace    

### More information:

* https://getcomposer.org/doc/01-basic-usage.md#package-names
* https://symfony.com/doc/current/bundles/best_practices.html#bundle-name
