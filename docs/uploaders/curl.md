---
title: cURL Config
description: cURL Uploader Config
slug: /uploaders/curl
---

You can upload files using this simple shell script. You can export the vars `$TOKEN` and `$HOST` in your `.bashrc` or `.zshrc`, or just replace them with your actual values.

```sh title="uploader.sh"
curl -H "Content-Type: multipart/form-data" -H "authorization: $TOKEN" -F file=@$1 $HOST
```

```sh title="uploader.sh copy to clipboard"
curl -H "Content-Type: multipart/form-data" -H "authorization: $TOKEN" -F file=@$1 $HOST/api/upload | xsel -ib
```