# inno-setup-action

This action can be used to create installer for any application in the workflow.

It bassed on InnoSetup, which is Inno Setup is a free installer for Windows programs by Jordan Russell and Martijn Laan...[more](https://jrsoftware.org/isinfo.php)


## Inputs 
#### `filepath`
**Required**  
**Description** - Path for ISS file


## usage 
First, you need to create InstallerScript.iss and insert it into the source code.
after that you use it in your workflow.

```
            -   uses: zhuzichu520/inno-setup-action@v1.0.0
                with: 
                    filepath: './path/InstallerScript.iss'
```
