# grunt-titanium-tishadow
> A template project with Grunt, Titanium and TiShadow.


## Dependencies
 * **Grunt** (~0.4.1)
   * **CoffeeScript** (coffee -> js scripts)
   * **Jade** (jade -> xml views)
   * **LTSS** (ltss -> tss styles)
   * **TiShadow** (deploy, test or execute codes lively)
 * **Titanium** (~3.1.2.GA)
   * **Alloy** (MVC framework)


## Directories
This project uses alloy framework with grunt so usually where you have to manage is `ti/src` folder.

 * **ti** - titanium app project
  * **app** - alloy dist folder
  * **src** - alloy source folder
  

## Usage

#### Build
```Shell
$ grunt build
```
#### Run TiShadow and watch
```Shell
$ grunt dev
```
#### Distribute
```Shell
$ ti build --platform <platform> -T <target> ...
```