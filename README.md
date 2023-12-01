# Welcome to (u)biquity : A Playnite Theme

<img src="https://raw.githubusercontent.com/RedSchism/ubiquity/main/screenshot01.jpg" />
**Addon: Extra MetaData Loader is required* for Full Features**

________________________________________________________________________________________






**::Questions and Answers::**


<details> 
  <summary>Q: After the Update the theme looks different / I liked the old style better. </summary>

<sub>All older versions of the theme are still supported and updated
   You can find the older styles of Ubiquity in the themes dir. in the "Theme Options" folder.</sub>
</details>


<details> 
  <summary>Q: I want to use a custom intro video but the video gets cut off!</summary>


<sub>Open "Main.xaml" with notepad++. Located in (Ubiquity/Views) folder.
   You will need to edit to entries here: </sub>

<sub>Under "< !--Intro Video-- >" look for the line "<DoubleAnimation.../ BeginTime="0:0:4.0" />"
   Change the "4.0" into the same length as your custom intro (ie"10" for 10sec)</sub>

<sup>Next search for "< !--Main-- >" look for the line "<DoubleAnimation.../ BeginTime="0:0:4.0" />"
   Repeat the steps above for the next entry
   Save and Restart ubiquity.</sup>
</details>



<details> 
  <summary>Q: I'm using Completion tags on the games but I don't like the color how do I change it?</summary>


<sub>Open "ListGameItemTemplate.xaml" with notepad++. Located in (Ubiquity/DerivedStyles) folder.</sub>

<sub>Search for (Background="#cd0057") Change the six digit color code here.
   You can write in the name of the color you want (ie:Background="Blue") or use a hex code for more 
   colors. 
   Save and Restart ubiquity.</sub>

<sub>Note: If your chosen color is too bright and the text can't be read you can change that
   in the same area (<TextBlock x:Name="CompletionStatus") under (Foreground="White")</sub>
</details>


 
<details> 
  <summary>Q: I liked it better when the Completion Status on the Infobar under the game logo.</summary>


<sub>Open "Main.xaml" with notepad++. Located in (Ubiquity/Views) folder.
   Search for (< !--GameTitles Infobar-- >) You should notice two TextBlock entries in green.</sub>
   
<sub>The green means they're disabled to enable them delete the "!--" and "--" from the green text.
   Once enabled the entries should be multiple colors. 
   Delete or Disable the duplicate entry below the reactivated code.
   Save and Restart ubiquity.</sub>
</details>



________________________________________________________________________________________

_*Extra Visual Options are available in the "Theme Options" Folder_
________________________________________________________________________________________

**::Completion status tags::**

To Enable/Disable Tags, in fullscreenmode "settings/visuals" Check/Uncheck 
"Darken not installed games".

<sub>If you want to have tags displayed as in the screenshots:</sub> 

In desktop mode enter "Library Manager" (Ctrl+W) / Completion Statuses and Add button 
enter term " New " as a category. Then on the right side in the dropdown menu select " New "
as "Default status assigned to newly added games" and "Remove" to the menu below that. 
________________________________________________________________________________________

**::Controller Icons::**

Input Icons are controlled by "Features" category.
If it appears empty for you ensure you have the following entries

- Full Controller Support
- Partial Controller Support
- Mouse and Keyboard

*Ideally each game should have only one of these active per game

**to have Full / Partial Controller Support Feature tags added automatically download
and install "Universal Steam Metadata" from the Add-ons Menu (Add-ons/Browse/MetadataSources)
________________________________________________________________________________________

_*Star Rating System is Calculated by Critic Score_
________________________________________________________________________________________

**::Extra MetaData Loader Settings:: <sub>(Optional)</sub>**

<sub>Open Add-ons Options ("F9") from the Playnite Desktop app, and edit logo settings.</sub>

**[Add-ons/Generic/Extra Metadata Loader/Logo Settings>Logo loader settings]**

- Max width = 600
- Max hight = 320

________________________________________________________________________________________

_*sidebar supports up to 14 icons (filters)_
________________________________________________________________________________________

**::Original Settings for the Classic Theme::**

**Theme Settings**

<sup>Playnite\Themes\Fullscreen\(u)biquity\Theme Options</sup>

- 1 . Main Page Styles = "4. Classic Theme"
- 2 . Game Details Page = "2.Details_Classic Theme"
- 3 . Color Scheme = "1. Classic Color Scheme"

<sub>COPY chosen theme options into theme main dir, unzip files and select YES to override</sub>

**Extra MetaData Loader Settings:**

<sup>Playnite Addons>Extensions Settings>Generic>Extra Metadata Loader> Logo Settings>Logo Loader Settings</sup>
- Max width = 600
- Max hight = 285

**Game Covers:**

<sup>Playnite Settings>GridView> Target aspect ratio = 1 : 1 (Preset: "Square")</sup>

**Fullscreen Theme Settings:**

<sup>Fullscreen Settings>Layout> </sup>
- Columns= 7
- Rows= 4
- Item Spacing= 20
