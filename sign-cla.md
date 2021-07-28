Sign the CLA
============

This page is the step-by-step guide to signing our Individual
Contributor License Agreement V3.0.

1. First and foremost, read [the current version of the CLA](cla.md).

2. Make an account on [GitHub](https://github.com/) if you don't already
   have one.

3. File a pull request on this project (the Aseprite Umbrella
   Project), as [outlined below](#filing-the-pull-request).

4. Email us, as [outlined below](#sending-the-email).

5. Wait for an Aseprite team member to merge your pull request. You may start
   opening pull requests for the project you're contributing to but we will
   only be able to merge your contributions after your signed CLA is merged.

If you wish to, you may also file the CLA in paper form. Please
see the instructions on [the paper CLA page](sign-cla-paper.md)
for details.

* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

Filing the Pull Request
-----------------------

If you don't yet know how to file a pull request, read [GitHub's
document about it](https://help.github.com/articles/using-pull-requests).

Make your pull request be the addition of a single file to the
[contributors](contributors) directory of this project. Name the file
with the same name as your GitHub userid, with `.md` appended to the
end. For example, for the user `danfuzz`, the full path to the file
would be `contributors/danfuzz.md`.

Put the following in the file:

```
[date]

I hereby agree to the terms of the Individual Contributor License
Agreement, version 3.0, with MD5 checksum
70c98242da1acddcd04197b6b2a4838d.

I furthermore declare that I am authorized and able to make this
agreement and sign this declaration.

Signed,

[your full real name]
https://github.com/[your github userid]
```

Replace the bracketed text as follows:

* `[date]` with today's date, in the unambiguous numeric form `YYYY-MM-DD`.
* `[your full real name]` with your full real name.
* `[your github userid]` with your GitHub userid.

You can confirm the MD5 checksum of the CLA by running the md5 program over `cla.md`:

```
md5 cla.md
MD5 (cla.md) = 70c98242da1acddcd04197b6b2a4838d
```

If the output is different from above, do not sign the CLA and let us know.

That's it!

* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

Sending the Email
-----------------

Send an email to [cla@aseprite.org](mailto:cla@aseprite.org),
with the subject "CLA" and the following body:

```
I submitted a pull request to indicate agreement to the terms
of the Individual Contributor License Agreement V3.0.

Signed,

[your full real name]
https://github.com/[your github userid]
[your address]
[your phone number]
```

Replace the bracketed text as follows:

* `[your full real name]` with your full real name.
* `[your github userid]` with your GitHub userid.
* `[your address]` with a physical mailing address at which you can be contacted.
* `[your phone number]` with a phone number at which you can be contacted.
