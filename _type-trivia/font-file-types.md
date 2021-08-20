---
layout: subpage
serial: level-3-type-trivia-subpage-4
---
These days, we don't need to be concerned with font file types as much as we used to. After all, we're mostly using cloud type services like Adobe Fonts, TypeKit and Google Fonts. With these services, the user isn't even made aware where the font files are stored on their computers. The whole process has been simplified for the user.

You may come across the need to actually purchase a font family to cater to a specific brand identity. When that happens, you'll need to know about the various kinds of font file types.

Note that I'm using the term font advisedly on this page. I'm referring to the actual file on your computer, not the type design.

![TrueType Fonts]({{site.url}}/svg/type-trivia/font-types-ttf.svg "TrueType"){:width="100px"}

TrueType
: This font type was developed by Apple in the late 1980's. It's still in use today. It's claim was to provide font creators pixel-level control called *hinting*. Ironically, today, most of the pixel-level information is ignored by modern operating systems. The OpenType format has mostly taken over from TrueType for quality fonts. The file has a .ttf file extension.

![PostScript Fonts]({{site.url}}/svg/type-trivia/font-types-ps.svg "PostScript Fonts"){:width="100px"}

PostScript
: These were invented by Adobe. They usually had two types of files per family. One was to view the type on-screen. The other was for printing. There are many different variants of PostScript fonts. Adobe recently [retired support](https://helpx.adobe.com/fonts/kb/postscript-type-1-fonts-end-of-support.html) for PostScript Type 1 fonts.

![OpenType Fonts]({{site.url}}/svg/type-trivia/font-types-otf.svg "OpenType Fonts"){:width="100px"}

OpenType
: OpenType is an extension to the TrueType format. They were invented by Microsoft with Adobe's support. They're the most common format today. The format's claim to fame is multi-language support and advanced glyph support.

![WOFF Fonts]({{site.url}}/svg/type-trivia/font-types-woff.svg "WOFF Fonts"){:width="100px"}

Web Open Font Format
: WOFF (the Web Open Font Format) is a web font format developed by Mozilla and other organizations. It boasts compression and includes license information if the author adds it. The format is actually a variant of either OpenType or TrueType. The font data is compressed, so sites using WOFF will tend to load faster. There are two versions called WOFF and WOFF2. The difference is simply their compression algorithms. In @font-face they are identified by the 'woff' and 'woff2' format descriptor respectively.
