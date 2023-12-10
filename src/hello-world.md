# Hello, World! <!-- -->

Now that you have installed Dawn (`dwn`), it is time to write your first Dawn program! It is traditional when learning a new programming language to write a little program that prints the text `Hello, world!` to the screen, so we’ll do the same here!

## Creating the project file

You may use any IDE, text editor or command line to create your first Dawn program. Dawn program files end with the extension `.dwn`.

If you are using command line, create an empty Dawn program file with:

### MacOS and Linux

```bash
cd <path to dawn program directory>
touch code.dwn
```

### Windows

(CMD)

```cmd
cd <path to dawn program directory>
copy NUL code.dwn
```

(PowerShell)

```powershell
Set-Location -Path <path to dawn program directory>
New-Item code.dwn -type file
```

## Adding the content

Open the file and add the following text:

```dwn
say "Hello, world!"
```

Then, open a command prompt or terminal and run the following:

### MacOS and Linux

```bash
dwn run code.dwn
```

### Windows

(CMD)

```cmd
dwn.exe run code.dwn
```

(PowerShell)

```powershell
& "dwn.exe" "run" "code.dwn"
```

## Result

You should get:

```console
Hello, world!
```
