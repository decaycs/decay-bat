<p align="center">
  <img align="center" width="128" height="128" src="https://raw.githubusercontent.com/decaycs/.github/main/assets/logo.png">
</p>

<h3 align="center">Decay-Bat</h3>

<p align="center">
	<img src="https://raw.githubusercontent.com/decaycs/decay-bat/main/assets/preview.png"/>
</p>

## Adding the themes

1. Clone this repository. 
2. First create a theme folder in bat's configuration directory by running:
    ```bash
	mkdir -p "$(bat --config-dir)/themes"
	```
3. Copy all the `.tmTheme` files from the cloned folder to bat's theme folder:
	```bash
	cp *.tmTheme "$(bat --config-dir)/themes"
	```
4. Rebuild bat's cache:
   ```bash
   bat cache --build
   ```
5. Run `bat --list-themes` and check if all the 4 theme flavours are present in the list. 
## Usage 

There are two ways to get the theme working. 
1. Add the following to bat's configuration file:
	```bash
	--theme="dark-decay"
	```
2. Using the `BAT_THEME` environmental variable:
   - Export the environmental variable inside your shell's configuration file: `BAT_THEME="dark-decay"`. The method to export the variable depends on your shell. 




## Thanks

- [Alxhr0](https://github.com/alxhr0)

