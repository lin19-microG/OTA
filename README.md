# Static Updater Resource for LineageOS OTA updates
This repository works as a static resource for the LineageOS Updater app for the specific builds provided within this organization.

## Branch 'changelog'
Here, plain test files with the naming convention **<device_name>_changelog.md** (example: hotdog_changelog.md) are stored and filled to provide the change log. To make the Updater app of LineageOS show this file instead of the original location used by LineageOS, the string `menu_changelog_url` needs to be overlaid with the "raw" view of the file.

Example:
```
<?xml version="1.0" encoding="utf-8"?>
<resources xmlns:xliff="urn:oasis:names:tc:xliff:document:1.2">

    <string name="menu_changelog_url" translatable="false">https://raw.githubusercontent.com/lin19-microG/OTA/changelog/hotdog_changelog.md</string>

</resources>
```

## Branch 'lineage-19.1'
Right now empty, but once such builds are regularly provided from here (e.g. because a specific device would not be offered by LineageOS originally), the respective device .json files will be created here. Documentation please see in next section.

## Branch 'lin-19.1-microG'
Json files of the naming **<device_name>.json** (example: hotdog.json) are stored here to tell the Updater app from where to fetch the updates.
To make this work, the system property `lineage.updater.uri` needs to be set as follows:
```lineage.updater.uri=https://raw.githubusercontent.com/lin19-microG/OTA/lin-19.1-microG/$(LINEAGE_BUILD).json``` 

See e.g. this commit: https://github.com/lin19-microG/android_vendor_lineage/commit/ae0f70031e2d34550bbcb68e1be310f6e9ab9a2e

The file format and contents are documented in the README of the `android_packages_apps_Updater` repository in the LineageOS org.
