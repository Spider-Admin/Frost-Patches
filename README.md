# Patches for Frost

A friend send me some patches for [Frost](http://jtcfrost.sourceforge.net/), which I used in the past to manually extract keys from Frost. He allowed me to release the patches under my name and license.

## Patches

| Patch                                   | Description                                                                                                                                                          | Status           |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------|
| Fix-Imports.patch                       | Required patch to build Frost. It fixes some imports.                                                                                                                | Required         |
| Filter-Good.patch                       | Allows filtering of good messages. Very helpful to view (and delete) the spam-messages.                                                                              | Optional         |
| Filter-Invalid-Messages.patch           | Ignores invalid messages, often caused by spammers. The invalid messages also caused some crashes, which is also fixes with this patch.                              | Optional         |
| Ignore-Duplicate-Keys-Add-Dialog.patch  | Remove duplicate keys before downloading them.                                                                                                                       | Optional         |
| Save-Downloaded-Keys.patch              | Immediately save the download-queue. By default the download-queue is only saved on exit of Frost.                                                                   | Optional         |
| Blocked-Not-Read.patch                  | Marks blocked messages as not read (new).                                                                                                                            | Optional, unused |
| Filter-Trash.patch                      | Hides trash-messages. A trash-message is a long message without keys and spaces. Since this patch produced many false-alarms, I don't use this patch anymore.        | Optional, unused |
| Log-Found-Messages.patch                | Writes the message-content of all found messages by the "Search messages"-dialog to the log-file. I used this patch to manually extract keys from Frost in the past. | Optional, unused |

## Contact

Author: Spider-Admin

Freemail: spider-admin@tlc66lu4eyhku24wwym6lfczzixnkuofsd4wrlgopp6smrbojf3a.freemail [^1]

Frost: Spider-Admin@Z+d9Knmjd3hQeeZU6BOWPpAAxxs

FMS: Spider-Admin

Sone: [Spider-Admin](http://localhost:8888/Sone/viewSone.html?sone=msXvLpwmDqprlrYZ5ZRZyi7VUcWQ~Wisznv9JkQuSXY) [^1]

I do not regularly read the email associated with GitHub.

## License

Frost-Patches by Spider-Admin@Z+d9Knmjd3hQeeZU6BOWPpAAxxs is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

[^1]: Link requires a running Freenet node at http://localhost:8888/
