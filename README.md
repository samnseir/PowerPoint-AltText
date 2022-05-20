# PowerPoint Alt Text
A macro-enabled Excel file for exporting and importing shapes/images' Alt Text from/to PowerPoint.
Saves an awesome amount of time on updating (eg translating) all the Alt Text in a PowerPoint presntation.

![PowerPoint-AltText](https://user-images.githubusercontent.com/2652773/169572561-21db91b7-b90c-48f8-b93a-bc2339acf441.gif)

## Download
[PowerPoint Alt Text.xlsm](https://github.com/samnseir/PowerPoint-AltText/raw/main/PowerPoint%20Alt%20Text.xlsm?download=1)
<br />**`SHA256`** `b7c8d526cbd487cbdd230510af523e73b623703ccefeeebc936849328f93158e`

## How to use
### Get
- Will get the Alt Text from the current open/active presentation, and if none are open, it will prompt you to select a presentation.
- Conditional Formatting:
  - Red = missing Alt Text
  - Yellow = autogenerated Alt Text
- Once the filename and path are present, then it will open and use that file.
- Shapes Names are clickable and will navigate to the slide and select the shape in PowerPoint.

### Update
- Add the new Alt Text in the second table - ensure it is entered/pasted as it correlates to the first table.
- You do not need to enter/paste the new Alt Text for every shape/image - you can add new Alt Text for one or more shapres (the script will skip empty or non-changed Alt Text).
- You can also change the Title and this will also be updated.
- After doing an update, do a get to see the new changes come through.
- After the update, you will need to save the presentation. You can also Undo in PowerPoint to revert the changes.

## Versions
- v1.6 - Check box added to generate thumbnails of the shapes/images
- v1.5 - Shape Names are clickable and will navigate to the slide and select the shape in PowerPoint.
