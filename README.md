## Lab 01

- Name: JD McMonagle 
- Email: mcmonagle.2@wright.edu

## Part 1 - GitHub Profile

1. https://github.com/JamesMcMonagle/JamesMcMonagle/blob/main/README.md
## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |   This will show info about commands fro powershell      |
| Get-Location | pwd    |   Shows info about your current location in powershell     |
| Get-ChildItem | ls    |    Gets the files from your system    |
| mkdir   | mkdir       |   Creates a new item    |
| Set-Location | cd     |   Makes the working station a specific location    |
| New-Item | touch      |   Makes a new Item  |
| Move-Item | mv        |   Moves in item to another location  |
| Copy-Item | cp        |   Copies an item from one location to another |
| Remove-Item | rm      |   Deletes an item like a folder or file     |
| notepad.exe | vim     |     This will open notepad in powershell   |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: PowerShell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory:$HOME
2. Create a directory named `DirA`: New-Item -Path "$HOME\DirA" -ItemType Directory
3. Create a directory named `Dir B`:New-Item -Path "$HOME\Dir B" -ItemType Directory
4. Go into `DirA`: Set-Location -Path "$HOME\DirA"
5. Go into `Dir B` from `DirA`: Set-Location -Path "$HOME\Dir B"
6. Return to your user's home directory:  Set-Location -Path $HOME
7. Create a file named `test.txt`:  New-Item -Path "$HOME\test.txt" -ItemType File
8. Move the file named `test.txt` into `DirA`:  Move-Item -Path "$HOME\test.txt" -Destination "$HOME\DirA\test.txt"
9. Contents of `test.txt`: Set-Content -Path "$HOME\DirA\test.txt" -Value
```
"Your're doing a great job keep going!!!"
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`:Set-Content -Path "$HOME\DirA\test.txt" -Destination "$HOME\DirA\copy.txt"
11. View the contents of `DirA`:  Get-ChildItem -Path "$HOME\DirA"
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item -Path "$HOME\DirA\test.txt" -Destination "$HOME\Dir B\fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item -Path .\fodder.txt, '.\Dir B' -Recurse -Force


## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.



