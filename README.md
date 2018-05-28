# Discord Translator Bot - Localization

This is the public localization project for **Discord Translator** - the most powerful translation bot for Discord.

Based on `Google Cloud Translate` and `Discord.js`.

[![Discord](https://discordapp.com/api/guilds/377112375372808193/embed.png)](https://discord.gg/uekTNPj) [![active servers](https://discordbots.org/api/widget/servers/360081866461806595.svg)](https://discordbots.org/bot/360081866461806595) [![invite](https://img.shields.io/badge/invite-Translator%20Bot-7289DA.svg)](https://discordapp.com/api/oauth2/authorize?client_id=360081866461806595&permissions=67628096&scope=bot)

<br>

## Translation Reuirements

* Must be a member of the official nvu.io Discord server (`i18n role`)
* Must have Poedit
* Must understand English
* General knowledge of Discord App and Discord terms

Bonus:

* Programming background
* Understanding of `Git`
* Experience with `gettext`

<br>

## How to Translate

* Download and Install [Poedit](https://poedit.net/)
* Download/clone this reposity to your computer
* Create a folder with your locale code if it does not exist, for example `fr/` for french
* Copy the files in the `en/` folder to your locale folder
* Open the copied files with *Poedit*
* Translate all messages to your language
* Save files
* Create pull request or message us on the [official Discord server](https://discordapp.com/invite/uekTNPj) if you do not know how to use Git

*You may also use any Text/Code editor to edit the `.po` files directly.*

<br>

### Translating Variables

Some strings contain variables, these are not meant to be translated, keep them intact like the following example:

English
```
Hello %s, how are you?
%d messages translated today.
```

German
```
Hallo %s, Wie geht's?
%d Nachrichten heute übersetzt.
```

`%s` refers to names/words (strings)

`%d` refers to numbers (digits)

<br>

### Text Formatters

Some messages may contain special formatting characters, such as `**` and `__` or `[word](%s)`, these are Markdown special characters, which styles words as **bold**, _underline_ etc. Here are some examples of correct translation in these cases:

English
```
__Hello **%s**__, how are you [today](%s)?
```
German
```
__Hallo **%s**__, wie geht es dir [heute](%s)?
```

<br>

### Contextual Translations

Some message strings contain a `context` note to help you understand the meaning more clearly, for example:

```
context: user

en: %s has been banned

de: %s wurde gebannt
```

If no context is provided, you are advised to provide a general translation.

<br>

### Gender

If your locale language translates `you` or `your` to a specific gender, then please use the equivalent of `they`, `them` and `their` for general/neutral addressing.

<br>

### Main English Texts

If you feel that the original English texts can be better, you are welcome to suggest improvements.

<br>

### Notes Summary

* Keep formatting intact
* Keep punctuation (`,.`) and newlines (`\n`)
* Use context when translating
* Gender-neutral translation

<br>

## Help

If you are not sure what to do, you can join the [official Discord server](https://discord.gg/uekTNPj) for discussions and guidance.

[![Discord](https://discordapp.com/api/guilds/377112375372808193/embed.png)](https://discord.gg/uekTNPj)
