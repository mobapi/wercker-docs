---
tags: cli
---

## How to install the CLI

You can obtain both versions for Mac OSX and Linux of the CLI at the
following locations:

* [Linux 32bit](https://s3.amazonaws.com/downloads.wercker.com/cli/stable/linux_386/wercker)
* [Linux 64bit](https://s3.amazonaws.com/downloads.wercker.com/cli/stable/linux_amd64/wercker)
* [Mac 64bit](https://s3.amazonaws.com/downloads.wercker.com/cli/stable/darwin_amd64/wercker)

For example downloading the Mac OSX version and
installing it in `/usr/local/bin`:

```no-highlight
# downloads the Mac OSX CLI to /usr/local/bin (YMMV)
curl https://s3.amazonaws.com/downloads.wercker.com/cli/stable/darwin_amd64/wercker -o /usr/local/bin/wercker
```

And for Linux 64 bit:

```no-highlight
# downloads the Linux CLI to /usr/local/bin (YMMV)
curl https://s3.amazonaws.com/downloads.wercker.com/cli/stable/linux_amd64/wercker -o /usr/local/bin/wercker
```
Next you want to make the CLI executable:

```no-highlight
chmod +x /usr/local/bin/wercker
```

You can use the `wercker version` command to see if a new version of the
CLI is available. See the [commands section](/docs/using-the-cli/available-commands.html) for more information.
Some commands require docker to be installed/available, see
[requirements](/docs/using-the-cli/requirements.html) for more information.
