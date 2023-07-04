
# Translating the server

The purposal for this repository is to create new translations, for new languages, turkish, german, russian, etc.

Any pull requests are welcome, please be sure to create your new language on the default format that it's already being done:




## How to do it?

#### XML Example:

```xml
	<window>
		<PTBR>Baixador de mapas</PTBR>
		<ENG>Map downloader</ENG>
		<ES>Descargador de mapas</ES>
	</window>
```

Be sure to choose a default symbol for your language, and use it over all strings.xml file, or, the translation will not work properly. So, in the example above, if you want to add a turkish translate to it, just do:

#### How to add your language:
```xml
	<window>
		<PTBR>Baixador de mapas</PTBR>
		<ENG>Map downloader</ENG>
		<ES>Descargador de mapas</ES>
        <TR>Harita indirici<TR>
	</window>
```

That's just an example, but that's how it will work. Your language will **only** be added to the live server once **all** the files are populated with your created language.

New files will be added from time passing, so you can be up-to-date on our discord:
> https://discord.gg/6km2j7NCaR

Send your github user that made pull requests to this repository on my private message, and you'll get a **beta tester** role on discord, where you'll be able to access the testing server, and help further, if you want.

# THE FILE [OTHER]/language/strings.xml CAN BE IGNORED !

