# microsoft-365-download
> https://config.office.com/
```
> Create New Config

> Office Suits
 = Office LTSC Proffetional Plus 2024 - Volume License

> Select Apps You Need

> Select Language
  = English (United States)

> Export As XML
```

Search - office deployment tool and download it.Then create a folder and move config.xml file and software to the folder.

Then click on the software and run it then select same folder. It will automatic create setup.exe

Now Open Command Prompt as Administator and open the folder by copy folder path then

```
cd folderpath~
example - cd C:\Users\User\Downloads\Office

setup.exe /configure Configuration.xml
```

