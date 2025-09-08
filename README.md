# triliumnext-theme-index 

INDEX is a dark theme.

## Examples

### Homepage

<img width="2710" height="1702" alt="image" src="https://github.com/user-attachments/assets/6905ceda-e167-4b83-aef5-4ddc93b6b885" />




## Setup Method as seen in original fork ( use this "INDEX.css file for orange liquid glass theme based on original font)

1. Install [TriliumNext](https://github.com/TriliumNext/Notes) (Tested in version v0.90.12).
2. Create a new note.
3. Inside the new note create another new note, and set the type to CSS.
4. Paste the code from the [INDEX](./INDEX.css) file.
5. Paste the code.
6. Set `Owned Attributes` to `#appTheme=INDEX`.
7. Add the font file [NotoSansMono](./NotoSansMono.ttf) the the first note which you created in step 2.
8. Set `Owned Attributes` to `#originalFileName=NotoSansMono.ttf #customResourceProvider="CONFIG/NotoSansMono.ttf"`
9. Restart the TriliumNext app.
10. Goto Setting>Appearance and set `Application Theme` to `INDEX`.
11. Set the `Code Syntax Highlighting for Text Notes` `Color Scheme` to `xt256 (DARK)`.
12. You may need to restart TriliumNext.

13.
14.  ---

15.  
16. ## SETUP METHOD FOR GTA STYLE FONT ( DIFFERENT THEME FROM THE ORINIAL. )
- Install [TriliumNext](https://github.com/TriliumNext/Notes) (Tested in version v0.90.12)
- Download the **Pricedown** font (GTA-style font) from one of these sources:
  - [FontBolt - GTA Font](https://www.fontbolt.com/font/grand-theft-auto-font/)
  - [Hyperpix - GTA Font](https://hyperpix.net/fonts/gta-font/)
  - [Free Fonts Vault - GTA Font](https://freefontsvault.com/grand-theft-auto-font/)

### Installation Steps

1. **Create Theme Note Structure:**
   - Create a new note in TriliumNext
   - Inside this note, create another new note and set the type to **CSS**

2. **Add Theme CSS:**
   - Copy and paste the code from the [INDEX.css](./INDEX.css) file into the CSS note
   - Set `Owned Attributes` to `#appTheme=INDEX`

3. **Add GTA-Style Font:**
   - Download the **Pricedown.ttf** font file from the sources above
   - Add the `Pricedown.ttf` file to the first note you created in step 1
   - Set `Owned Attributes` to:
     ```
     #originalFileName=Pricedown.ttf
     #customResourceProvider="CONFIG/Pricedown.ttf"
     ```

4. **Apply Theme:**
   - Restart TriliumNext
   - Go to **Settings > Appearance**
   - Set `Application Theme` to `INDEX`
   - Set `Code Syntax Highlighting for Text Notes` `Color Scheme` to `xt256 (DARK)`
   - Restart TriliumNext again if needed

### Features
- **GTA-Style Typography:** Uses Pricedown font with Orbitron and Rajdhani as fallbacks
- **Pronounced Liquid Glass Effects:** Enhanced blur, saturation, and transparency effects
- **Dark Burnt Orange Theme:** Rich, warm color palette with glass-like transparency
- **Modern UI Elements:** Rounded corners, smooth animations, and enhanced shadows
- **Accessibility:** High contrast mode support and reduced motion options

### Fallback Fonts
If the Pricedown font is not available, the theme will automatically fall back to:
1. Orbitron (Google Fonts)
2. Rajdhani (Google Fonts) 
3. Arial Black
4. System sans-serif fonts

