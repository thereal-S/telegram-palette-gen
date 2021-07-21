# Installation

```bash
git clone --depth 1 https://github.com/matteoguarda/telegram-palette-gen ~/.telegram-palette-gen
cd ~/.telegram-palette-gen
./telegram-palette-gen
```

# Generate the color palette

```bash
# If you want to use the colors generated by pywal/wal.
~/.telegram-palette-gen/telegram-palette-gen --wal

# If you want to use a 16-colors palette of yours.
~/.telegram-palette-gen/telegram-palette-gen --palette '/path/to/palette.sh'
```

# Set the color palette

To set the palette follow these steps:

1. Open telegram, go to "settings/chat background" and click on choose from file:

![instruction 1](https://user-images.githubusercontent.com/40271651/42967114-863e1890-8b9f-11e8-80f5-3b52ff75cdef.png)

2. Toggle hidden files (in english that's show hidden files):

![instruction 2](https://user-images.githubusercontent.com/40271651/42967489-b054cf42-8ba0-11e8-925d-7ca11597a537.png)

3. Double click on ~/.cache/telegram-palette-gen/colors.tdesktop-palette:

![instruction 3](https://user-images.githubusercontent.com/40271651/42967681-5592a5ce-8ba1-11e8-83f3-195d3c14f3f8.png)

4. Click on keep changes:

![instruction 4](https://user-images.githubusercontent.com/40271651/42968072-8a87aa8a-8ba2-11e8-85d7-8c4de2ceb391.png)

5. Double click on ~/.cache/telegram-palette-gen/background.png or jpg depending on your wallpaper:

![instruction 5](https://user-images.githubusercontent.com/40271651/42967685-58456ba8-8ba1-11e8-8ea4-897177b9b18f.png)

# Updating

You can update telegram-palette-gen by running git pull inside ~/.telegram-palette-gen:
```bash
cd ~/.telegram-palette-gen
git pull
```

# Screenshots

<img src="https://user-images.githubusercontent.com/40271651/42736395-79242280-8866-11e8-8419-a9dc0b22be4c.png" alt="demo" align="center">
<img src="https://user-images.githubusercontent.com/40271651/42736398-7e628d04-8866-11e8-9b40-ee09c09910d7.png" alt="demo" align="center">
<img src="https://user-images.githubusercontent.com/40271651/42736400-81f08110-8866-11e8-860d-d71c3e1b4c10.png" alt="demo" align="center">

# Palette specifications

If you want, you can import the colors from a shell script that needs to be written in the following way:

```bash
# For example:

color0='#263238'
color1='#f07178'
color2='#c3e88d'
color3='#ffcb6b'
color4='#82aaff'
color5='#c792ea'
color6='#89ddff'
color7='#eeffff'
color8='#546e7a'
color9='#f78c6c'
color10='#c3e88d'
color11='#ffcb6b'
color12='#82aaff'
color13='#37474f'
color14='#89ddff'
color15='#eeffff'
```

# Important notes

Some color constants in colors.tdesktop-palette are marked as // [UNTESTED], this because I couldn't find the elements responsable in the app.
So if you find something strange open an issue (with a screenshot of the element and it's name if possible) and I'll fix.

You can also use light colorschemes, no need for extra option, just run the script normally.

The palette works with [wal] too, not just [pywal] and with every color palette that respects the specifications mentioned above.

[pywal]: https://github.com/dylanaraps/pywal
[wal]: https://github.com/dylanaraps/wal

.