# Obsidian Banner Snippet

This banner uses the CSS snippet approach as opposed to using a plugin that risks becoming incompatible with future versions of Obsidian. If this snippet does become incompatible, it could easily be configured to be compatible with the latest Obsidian version.

You can refer to [Obsidian help](https://help.obsidian.md/Extending+Obsidian/CSS+snippets) website to learn how to add the banner snippet.

The snippet can be enabled in the **CSS snippets** setting.

## Enable the Banner

![Enable Banner](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/enable-banner.png)

Enter *banner* into the **cssclasses** frontmatter property.

In the body, type in `![[image path/name|banner]]` like the example in the image. Adding the `|alias` indicates the attachment is the banner.

## Banner Icon

![Banner Icon](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/banner-icon-1.png)

A banner icon can be added by making a callout. For example, `> [!banner-icon] <icon>`. Replace *\<icon\>* with an emoji.

The banner should now look like the following image.

![Banner Icon](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/banner-icon-2.png)

## Banner Inline Title

You can position the **Inline Title** on top of the banner. However, ensure that you have the **Inline Title** setting enabled under **Appearance** in Obsidian settings.

Once the setting has been enabled, enter *banner-inline-title* into the **cssclasses* property. The inline title will now look like the following image.

![Banner Inline Title](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/banner-inline-title-1.png)

## Style Settings

The banner snippet supports the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.

For further adjusments, navigate to Obsidian settings and to **Style Settings** where you can adjust the position and color of a few of the banner's elements.

![Banner Style Settings](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/banner-style-settings-1.png)
![Banner Style Settings](https://github.com/HandaArchitect/obsidian-banner-snippet/blob/88a18587e1f800039b723db590bb8c30ab1eb21e/Images/banner-style-settings-2.png)
