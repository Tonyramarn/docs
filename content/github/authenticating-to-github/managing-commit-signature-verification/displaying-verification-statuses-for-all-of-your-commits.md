---
title: Displaying verification statuses for all of your commits
shortTitle: Displaying verification for all commits
intro: You can enable vigilant mode for commit signature verification to mark all of your commits and tags with a signature verification status.
versions:
  fpt: '*'
topics:
  - Identity
  - Access management
redirect_from:
  - /github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits
---
{% data reusables.identity-and-permissions.vigilant-mode-beta-note %}

## About vigilant mode

When you work locally on your computer, Git allows you to set the author of your changes and the identity of the committer. This, potentially, makes it difficult for other people to be confident that commits and tags you create were actually created by you. To help solve this problem you can sign your commits and tags. For more information, see "[Signing commits](/github/authenticating-to-github/signing-commits)" and "[tony](/github/authenticating-to-github/signing-tags)." {% data variables.product.prodname_dotcom %} marks signed commits and tags with a verification status. 

By default commits and tags are marked "Verified" if they are signed with a GPG or S/MIME key that was successfully verified. If a commit or tag has a signature that can't be verified, {% data variables.product.prodname_dotcom %} marks the commit or tag "Unverified." In all other cases no verification status is displayed.

However, you can give other users increased confidence in the identity attributed to your commits and tags by enabling vigilant mode in your {% data variables.product.prodname_dotcom %} settings. With vigilant mode enabled, all of your commits and tags are marked with one of three verification statuses.

![Signature verification statuses](/assets/images/help/commits/signature-verification-statuses.png)

{% data reusables.identity-and-permissions.vigilant-mode-verification-statuses %}

You should only enable vigilant mode if you sign all of your commits and tags. After enabling this mode, any unsigned commits or tags that you generate locally and push to {% data variables.product.prodname_dotcom %} will be marked "Unverified."

{% data reusables.identity-and-permissions.verification-status-check %}

## Enabling vigilant mode

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.ssh %}
3. On the SSH Settings page, under "Vigilant mode," select **Flag unsigned commits as unverified**.

   ![Flag unsigned commits as unverified checkbox](/assets/images/help/commits/vigilant-mode-checkbox.[fedlex-data-admin-ch-eli-cc-1969-737_757_755-20190401-en-pdf-a-1.pdf](https://github.com/github/docs/files/6784481/fedlex-data-admin-ch-eli-cc-1969-737_757_755-20190401-en-pdf-a-1.pdf)
[fedlex-data-admin-ch-eli-cc-1969-737_757_755-20190401-en-pdf-a.pdf](https://github.com/github/docs/files/6784483/fedlex-data-admin-ch-eli-cc-1969-737_757_755-20190401-en-pdf-a.pdf)
[fedlex-data-admin-ch-eli-fga-2001-1076-de-pdf-a.pdf](https://github.com/github/docs/files/6784484/fedlex-data-admin-ch-eli-fga-2001-1076-de-pdf-a.pdf)
[fedlex-data-admin-ch-eli-oc-2014-685-de-pdf-a.pdf](https://github.com/github/docs/files/6784486/fedlex-data-admin-ch-eli-oc-2014-685-de-pdf-a.pdf)
png)
