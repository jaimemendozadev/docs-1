---
description: How to obtain and use an ID Token.
toc: true
topics:
  - tokens
  - id-tokens
contentType:
  - how-to
  - concept
useCase:
  - invoke-api
---
# ID Token

## Overview

The ID Token is a <dfn data-key="json-web-token">JSON Web Token (JWT)</dfn> that contains user profile information (including items such as the user's name and email) which is represented in the form of **claims**. These claims are statements about the user, which can be trusted if the consumer of the token can [verify its signature](/tokens/guides/id-token/validate-id-token#verify-the-signature).

You can [get an ID Token](/tokens/guides/id-token/get-id-tokens) for a user after they successfully authenticate.

::: warning
Υou __must__ [validate the ID Token](/tokens/guides/id-token/validate-id-token) before storing and using it.
:::

Additionally, you can learn about your options for renewing a token. Which option to use depends on the type of application you have, and is covered in more detail in the [Refresh Tokens](/tokens/refresh-token/current) document.

## Keep Reading

::: next-steps
* [How to get an ID Token](/tokens/guides/id-token/get-id-tokens)
* [How to validate an ID Token](/tokens/guides/id-token/validate-id-token)
* [Overview of JSON Web Tokens](/jwt)
* [JWT Structure](/tokens/reference/jwt/jwt-structure)
* [IETF RFC for JWT](https://tools.ietf.org/html/rfc7519)
* [Debugger for Viewing JSON Web Tokens](http://jwt.io/)
:::
