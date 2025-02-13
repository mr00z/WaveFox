# *WaveFox*

##### Minimum Requirements
- Firefox 110
- Windows
- MacOS
- Linux

##### Installation

- Download the `chrome` folder and put it in your user profile folder. For convenience, use `about:profiles`
- Go to `about:config` and activate the keys below

  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `layout.css.color-mix.enabled`
  - `layout.css.has-selector.enabled` (Firefox 113+ && v1.5.113 Beta)
  - `svg.context-properties.content.enabled` (Activate this key if the menu icons / tab corners do not follow the general design color. Previously seen only on MacOS)
  
- Specify the desired shape of the tabs.

  <details>
  <summary>Creation of keys</summary>
  Restart your browser for the changes to take effect.
  
  ![изображение](https://user-images.githubusercontent.com/85301851/180253017-22325fad-2f53-47f5-b409-618ca7fe6084.png)
  ![изображение](https://user-images.githubusercontent.com/85301851/180253209-3e6965a9-641a-4ac2-bf3d-242ac8b3451c.png)
  </details>

  ##### Proton
  ![Proton](https://user-images.githubusercontent.com/85301851/180247798-3685fad6-cc4e-49ad-9b0e-7664354233ff.PNG)
  - `userChrome.ProtonTabs-Enabled`
  
  ##### Photon
  ![Photon](https://user-images.githubusercontent.com/85301851/180248812-8aecba52-77bd-4ee5-9e04-e6f07276dfa4.PNG)
  - `userChrome.PhotonTabs-Enabled`

  ##### WaveFox
  ![WaveFox](https://user-images.githubusercontent.com/85301851/180248857-fee4dd92-6d6c-4c34-8615-bf69e740f2bd.PNG)
  - `userChrome.WaveFoxTabs-Enabled`

  ##### Chrome
  ![Modern Chrome](https://user-images.githubusercontent.com/85301851/180248907-bdcf4ffc-fd4a-4923-b97d-a0b0b0cf5ee2.PNG)
  - `userChrome.ChromeTabs-Enabled`

  ##### Edge
  ![Edge](https://user-images.githubusercontent.com/85301851/180248952-faa55898-0243-4cdf-ba6a-33513184398f.PNG)
  - `userChrome.EdgeTabs-Enabled`

  ##### Australis
  ![Australis](https://user-images.githubusercontent.com/85301851/180248996-2f21d3b0-e33b-4feb-bbfc-2859df714344.PNG)
  - `userChrome.AustralisTabs-Enabled`

  ##### Chrome (Legacy)
  ![Legacy Chrome](https://user-images.githubusercontent.com/85301851/180249039-350dd21d-51ee-432b-a79d-0c82861e7d43.PNG)
  - `userChrome.LegacyChromeTabs-Enabled`

## Optional

### Windows System Effects
Works with modern versions of Windows 11 / Windows 10. System effects must be supported on the operating system side. Otherwise, you need third-party software, such as Mica For Everyone. You also need to disable the accent color in the operating system settings, if it was enabled. Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/160720915-a055134a-357c-44cc-a638-8dd56e869111.png)

Download and install Mica For Everyone from [here](https://github.com/minusium/MicaForEveryone/releases).

- `userChrome.Windows.SystemEffects.Enabled`

### Toolbar Transparency
Works only with the system theme.
![изображение](https://user-images.githubusercontent.com/85301851/165526704-4f7486c4-f330-4c86-a25d-6ed8ab2affe4.png)

- `userChrome.Toolbar.Transparency.Low.Enabled`
- `userChrome.Toolbar.Transparency.Medium.Enabled`
- `userChrome.Toolbar.Transparency.High.Enabled`
- `userChrome.Toolbar.Transparency.VeryHigh.Enabled` (Proton Tabs Only)

### Linux Transparency
Requires Linux with transparency support. Tested on Linux Manjaro KDE + ForceBlur. Transparency is active for all modes, but does not work everywhere. This may change with future browser updates. Works only with the system theme.

![изображение](https://user-images.githubusercontent.com/85301851/173119832-e82bc2f7-eda7-4167-9dcd-ccca50383816.png)

- `userChrome.Linux.Transparency.Enabled`
- `gfx.webrender.all` (Required key)

### Tab Frame
The tab frame consists of type, color and saturation. Not compatible with themes that use a translucent toolbar.
![изображение](https://user-images.githubusercontent.com/85301851/152011749-4d5619b3-0fd8-40f9-a3dc-96be31839971.png)

##### Light Theme

###### Type
- `userChrome.LightTheme.TabFrameType.Border.Enabled`
- `userChrome.LightTheme.TabFrameType.Shadow.Enabled`
###### Color
- `userChrome.LightTheme.TabFrameColor.Auto.Enabled`
- `userChrome.LightTheme.TabFrameColor.White.Enabled`
- `userChrome.LightTheme.TabFrameColor.Black.Enabled`
###### Saturation
- `userChrome.LightTheme.TabFrameSaturation.Low.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.Medium.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.High.Enabled`
- `userChrome.LightTheme.TabFrameSaturation.VeryHigh.Enabled`

##### Dark Theme

###### Type
- `userChrome.DarkTheme.TabFrameType.Border.Enabled`
- `userChrome.DarkTheme.TabFrameType.Shadow.Enabled`
###### Color
- `userChrome.DarkTheme.TabFrameColor.Auto.Enabled`
- `userChrome.DarkTheme.TabFrameColor.White.Enabled`
- `userChrome.DarkTheme.TabFrameColor.Black.Enabled`
###### Saturation
- `userChrome.DarkTheme.TabFrameSaturation.Low.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.Medium.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.High.Enabled`
- `userChrome.DarkTheme.TabFrameSaturation.VeryHigh.Enabled`

### Tab Separators
![изображение](https://user-images.githubusercontent.com/85301851/152351312-f6ad4578-e7d5-40b7-8b2d-49388a750f54.png)

- `userChrome.TabSeparatorsLowSaturation-Enabled`
- `userChrome.TabSeparatorsMediumSaturation-Enabled`

### Menu Density
By default context menus follow the selected interface density, but it is possible to set a fixed size.

| Compact | Normal | Touch |
|---------|--------|-------|
| ![изображение](https://user-images.githubusercontent.com/85301851/152645825-7d351e3e-b938-4fa1-a460-1f699ed1c3c6.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645878-d917e841-837a-4a11-8fc1-ce0fc2262aef.png) | ![изображение](https://user-images.githubusercontent.com/85301851/152645915-833c1b22-e320-445f-817e-408ea26f7605.png) |

- `userChrome.CompactContextMenu-Enabled`
- `userChrome.NormalContextMenu-Enabled`
- `userChrome.TouchContextMenu-Enabled`

### Icons

| Regular | Filled |
|---------|--------|
| ![изображение](https://user-images.githubusercontent.com/85301851/151192118-0cbdb5a7-a77f-4275-8841-2ac321657c86.png) | ![изображение](https://user-images.githubusercontent.com/85301851/151192708-5ae7691c-ce07-49d8-b4fb-fc58692b63fe.png) |

- `userChrome.RegularMenuIcons-Enabled`
- `userChrome.FilledMenuIcons-Enabled`

### Drag Space
![изображение](https://user-images.githubusercontent.com/85301851/152680229-43547df0-1d2c-4384-b024-950e7aa56ca6.png)

- `userChrome.DragSpace.Left.Disabled`
- `userChrome.DragSpace.Right.Disabled`
- `userChrome.DragSpace.Top.Windowed.Enabled`
- `userChrome.DragSpace.Top.Maximized.Enabled`
- `userChrome.DragSpace.Top.Fullscreen.Enabled`

### Pinned Tabs Width
![Снимок](https://user-images.githubusercontent.com/85301851/185612113-7bb0445f-8993-45bd-916d-d066e88ea7f4.PNG)

- `userChrome.PinnedTabsWidthLowIncrease-Enabled`
- `userChrome.PinnedTabsWidthHighIncrease-Enabled`

### One Line
![Снимок](https://user-images.githubusercontent.com/85301851/181300272-d1ecfc93-898a-4eb3-80b9-9974fc471b45.PNG)

- `userChrome.OneLine.TabBarFirst.Enabled`
- `userChrome.OneLine.NavBarFirst.Enabled`
- `browser.tabs.inTitlebar` (Enable this key if there are problems with window control buttons. Set the value to 0)

Low values are more suitable for high resolution monitors.
- `userChrome.OneLine.NavBarWidth.Low.Enabled`
- `userChrome.OneLine.NavBarWidth.Medium.Enabled`
- `userChrome.OneLine.NavBarWidth.High.Enabled`

### Tabs On Bottom
![изображение](https://user-images.githubusercontent.com/85301851/182421633-3ec6948a-85cb-47ac-8b6d-6e92293e4ca3.png)

- `userChrome.TabsOnBottom-Enabled`
- `browser.tabs.inTitlebar` (Required key. Set the value to 0)
