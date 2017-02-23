# CHANGELOG for dotnetframework

This file is used to list changes made in each version of dotnetframework.

## 1.3.2
- Changed reboot action back to `:request_reboot`.

## 1.3.1
- Changed reboot action to `:reboot_now` instead of `:request_reboot`.

## 1.3.0
- Added a 1 minute delay in reboot command to help with VMware vRO.

## 1.2.0
- .NET 4.6.1 support
- Installation is skipped if a newer .NET version is already installed.
- Mini-tests do not fail if a newer .NET version is already installed.

## 1.1.0
- Fixed .NET framework idempotence to avoid constant reboots
- Added dotnetframework_version LWRP

## 1.0.0:
- Initial version released on Supermarket.

- - -
Check the [Markdown Syntax Guide](http://daringfireball.net/projects/markdown/syntax) for help with Markdown.

The [Github Flavored Markdown page](http://github.github.com/github-flavored-markdown/) describes the differences between markdown on github and standard markdown.
