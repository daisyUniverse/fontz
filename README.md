# fontz
just some fonts that ive made

# Converting fonts into psuedo bitmap fonts
You're gonna need...
[FontForge](https://fontforge.org/en-US/)
[Bits'n'Picas by KreativKorp](https://github.com/kreativekorp/bitsnpicas)

1. open your source TTF in FontForge
2. `Element` -> `Bitmap Strikes Available` -> Set pixel sizes to desired render size
   2b. You may need to remove all the glyphs you don't need in order for this to work. You can do this by:
   2c. Selecting the Glyphs you want to keep, going to `Edit` -> `Selection` -> `Invert Selection`, and then going to `Encoding` -> `Detatch and Remove Glyphs`
4. `Element` -> `Regenerate Bitmap Glyphs` -> Same size, select 'All Glyphs' on the dropdown on the top of the dialogue window
5. `File` -> `Generate Fonts` (should have all the right settings already, save it as a .BDF
   5b. (set number it asks to 72)

7. Open the .BDF in Bits'N'Picas
8. `File` -> `Export`
9. Pixel Width & Pixel height = 100
10. Export

# Font resources

## [Pentacom's BitFontMaker2](https://www.pentacom.jp/pentacom/bitfontmaker2/)
![image](https://github.com/user-attachments/assets/e0614d70-0230-425c-9936-0a5718f2e9a2)

( Completely online bitmap font generator, works very well! )

## [VileR's Old school PC Font resource](https://int10h.org/oldschool-pc-fonts/)
![image](https://github.com/user-attachments/assets/9bd8e8c2-ebc1-4055-a5d2-d625a4ef469a)

( Especially the readme section. Lots of really good info in there )
