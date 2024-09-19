###### *<div align = right><sub>// design by t2</sub></div>*
<div align = center>
<img src="https://raw.githubusercontent.com/prasanthrangan/hyprdots/main/Source/assets/hyde_banner.png">
<br><br></div>

## Hyprlock Configuration
This repository contains the Hyprlock configuration files and layout settings. Below are the different layouts with their respective screenshots and descriptions.

## Layout 1

![Layout 1](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout1.png)
Description: This layout features a minimalistic clock display with a greeting message.

## Layout 2

![Layout 2](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout2.png)
Description: This layout includes a clock display and a music widget showing the currently playing track from Spotify.

## Layout 3

![Layout 3](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout3.png)
Description: This layout showcases a clock display, weather & battery information, and a music widget with an album sync background.

## Layout 4

![Layout 4](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout4.png)
Description: This layout features a clock display with a background image and additional widgets.

## Layout 5

![Layout 5](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout5.png)
Description: This layout includes a clock display with a gradient background and a greeting message.

## Layout 6

![Layout 6](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout6.png)
Description: This layout showcases a clock display with a custom background and a music widget.

## Layout 7

![Layout 7](https://raw.githubusercontent.com/mahaveergurjar/Hyprlock-Dots/main/screenshots/layout7.png)
Description: This layout features a clock display with a background image and a weather widget.

## Layout 8

![Layout 8](https://raw.githubusercontent.com/rishav12s/Hyprlock-Dots/main/screenshots/layout8.jpg)
Description: This layout is a combination of layout 1 with layout 2 widgets

## Layout 9

![Layout 9](https://raw.githubusercontent.com/rishav12s/Hyprlock-Dots/main/screenshots/layout9.jpg)
Description: This layout has stylish date and clock along with battery widget

## Layout 10

![Layout 10](https://raw.githubusercontent.com/rishav12s/Hyprlock-Dots/main/screenshots/layout10.png)
Description: This layout is inspired from MacOS and uses Apple's SF font

## Layout 11

![Layout 11](https://raw.githubusercontent.com/rishav12s/Hyprlock-Dots/main/screenshots/layout11.png)
Description: This layout has pngs to make it look unique and cool

...

## Installation and Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/rishav12s/Hyprlock-Dots.git
    ```
2. Copy the configuration files to your Hyprlock directory:
    ```bash
    cp -r Hyprlock-Dots/Configs/.config/* ~/.config/
    ```
3. Copy the fonts folder to fonts directory :
    ```bash
    cp -r Hyprlock-Dots/Fonts/* ~/.local/share/fonts/
    ```
4. Make the scripts executable :
    ```bash
    chmod +x ~/.config/hyprlock/scripts/*
    ```
5. Add Hyprlock to your hyprland keybings and wlogout menu :
    ```bash
    bindl = $mainMod, L, exec, hyprlock #launch hyprlock
    ```

## Customization

You can customize the layouts by editing the respective configuration files located in the `~/.config/hyprlock/` directory.

## Issues

If you face any issues, please open an issue in this repository.
