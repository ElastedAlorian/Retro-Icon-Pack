# Retro Icon Pack

Welcome to the **Retro Icon Pack**! This repository serves to provide you with free, open source, and very retro looking icons for your devices! This repository is still new, but I hope that one day we'll have a good amount of icons in a neat little "database" of sorts!

# File Structure

This is still to be determined, but at the moment the planned format is:

> Aesthetic -> App -> Files of icons for said app. (If there are multiple variants then they may be seperated into folders.)

I hope I can figure this out in an easily digestable manner. I feel some of the concepts I have here could be explained better in video form or with better formatting, so if it's confusing, I apologize in advance!

# Software with Provided Icons

- Kate Editor - Windows Aero/Aqua style by [ElastedAlorian](https://www.github.com/ElastedAlorian)
    - In formats of: `png`, `af`, and `svg`

# Planned Aesthetics and Structure

## Aesthetics
```
> Official Retro Icons

    > Windows Icons
        > Windows Classic (Icons in the style of Windows 95 to 2000)
        > Windows Luna (Icons in the style of Windows XP)
        > Windows Aero (Icons in the style of Windows Vista, 7, 8.x, and maybe late-era XP as well.)
            > Late Windows XP
            > Windows Vista
            > Windows 7
            > Windows 8
        > Windows Metro (Metro Icons from Windows 8.x, 10, 10X, and early 11.)
            > Windows 8 Metro Icons + Tiles
                > Windows 8.1 Metro Icons + Tiles
            > Windows 10
            > Windows 10X and Early Windows 11
        > Primitive Windows Icons?
            > (For those EARLY era days! From Windows 1.0 prototypes to Windows 3.x and maybe early NT versions.)
   
   > macOS Icons
        > Early Aqua (from Mac OS X (10)  up until macOS 10.10 Yosemite)
        > Flat Design (from macOS Yosemite until whichever version made the icons have more depth, maybe Monterey?)
        
    > Linux icons?
        > Please provide icons here *only* if they cannot be found in any existing icon packs.
        
    > Other icons
        > Early Android icons
        > Early iOS Icons
        > Whatever is over ten years old and can count here.
        
    Icons from software prototypes may count as long as they are labelled as such.
    So for example, an icon for Windows Media Player may be found in say:
        > Windows Aero -> Windows Vista -> icon.ico 
    Or for say, Paint, back when it was "Windows Paint" and not simply "Paint" or "Microsoft Paint"
        > Windows Primitive -> Windows 1-2 -> Windows Paint -> icon.png
```


``` Community Retro Icons (Folder Name)
    > Classicly Flat (Y2K Flat)
        > Something that feels like it could've came from the early 2000's. Flat icons inspired by the flat design of the era may be included.
    > Frutiger Aero (Y2K Gloss)
        > Something that feels like software from the early/mid 2000's to the early 2010's. I hate using the term "Frutiger Aero" for this unrionically, but it was the closest thing I had before it sounded generic.
    > Newly Flattened (2010s Newly Flattened)
        > Back when flat design became mainstream again in the early/mid 2010's,
```

## Planned File Structure
```
> Example Software
            > variant A by personONE
                > icon in png format
                    > for multipurpose
                > icon in any sort of modifiable format (recommended)
                > icon in svg, ico, or icns (extra recommended)
                    > svg for general multipurpose/multi-system use while retaining quality when resized
                    > ico, usually for Windows icon substitution. It *may* work on Linux, but in small instances,  iso files may appear corrupted.
                    > icns for replacing icons internally with macOS apps. Not required, but it's nice.
            > variant B by personTWO
                > should follow a similar format
            > readme explaining and showing the variants
```
This is the planned file structure, but there may be some curiosities  with it I'll try to address:
- Multiple official variants for a software under a certain era.
    - If an app has multiple design variants for an era, such as Internet Explorer having two versions of the icon during the Windows 7 days), then they still may have the chance of being in multiple folders if there's plenty. But if there's like only two versions then you could put every good file variation into one folder with the readme. 
        - For instance: `icon-early` and `icon-lateera` both can be subfolders, but if both have few format variations, such as just one `png` and `ico` file, then it would not hurt to have them in one folder.
        - I would advise for this not to be the case with custom icons however, just to avoid any mix-up between artists!
- An app having multiple official icons per multiple eras.
    - In this case, the app's folder title would be in each era honestly.
        - Example, Internet Explorer would be in the folders for Windows Classic (as it originated for Windows 95) but it would also be in the folders for say Windows Luna (due to its inclusion with Windows XP) as well as the Early Aqua folder for the macOS icons due to it also being originally an early Mac app as well. (Even if it's not as nessesary to have IE in the macOS category.)
        
# Contributing
When this repository is better suit for contributing, there are only a few things expected from you:
1. An icon for an app.
    - This app can be a new addition to the repo, or contributing to an existing icon.
2. It must be in a standard format.
    - If you created it, we expect it to be in `png` format, but we also encourage users to upload the project files (like how GitHub is designed for Open Source) but we do not enforce it.
        - For example, a project created with Affinity by Canva may have a file labelled with `af` or `aftemplate` at the end, this would be accepted! Photoshop (and others) may utilize `psd`, and so on.
    - If you're ripping it from a software, it would also be appreciated if the original icon was also put alongside it.
        - So it would be something like `icon.png` as well as `icon.ico/icns`
3. All credit and info be due and correct!
    - If your icon was made by a friend, then you must credit your friend! If it was taken from a software or logo, then it must be said where it was from. So if you [grabbed an icon from a website](https://thumb.wikimedia.org/wikipedia/commons/thumb/b/b8/Microsoft_Edge_logo_%282015%E2%80%932019%29.svg/960px-Microsoft_Edge_logo_%282015%E2%80%932019%29.svg.png?utm_source=en.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail) then you must [credit the website](https://en.wikipedia.org/wiki/Microsoft_Edge_Legacy) as the source you got it from. For instance, I grabbed the icon for Microsoft Edge Legacy from the Wikipedia page on it!
    
    Happy contributing!
