# Twitch Commands Page

This document describes a simple web page designed to display various Twitch commands, categorized into different groups. The page includes search functionality and a dropdown for filtering commands based on their category.

## HTML Structure

### Head Section

- **DOCTYPE Declaration**: Specifies that this document is an HTML5 document.
- **Language**: Set to English (`<html lang="en">`).
- **Character Set**: UTF-8 is used for character encoding.
- **Viewport**: Meta tag for responsive design, adjusting the layout on different devices.
- **Title**: The title of the page is "Twitch Commands".
- **Styles**: Contains internal CSS for styling various elements of the page.

### Body Section

1. **Main Heading**: 
   - `<h1>Twitch Commands</h1>` - A centered title with light color for contrast against a gradient background.

2. **Control Container**:
   - A flex container holding:
     - **Search Input**: Allows users to search commands.
     - **Group Select Dropdown**: Lets users filter commands by categories (Twitch, Song, Setup, Social, Valorant).

3. **Command List Container**:
   - Contains all command categories, each with a title and associated commands.

   #### Command Categories
   - **Twitch Commands**: 
     - Commands: `!lurk`, `!iq`, `!watchtime`
   - **Song Commands**:
     - Commands: `!song`, `!next`, `!pos`
   - **Setup Commands**:
     - Commands: `!pc`, `!setup`
   - **Social Commands**:
     - Commands: `!discord`, `!socials`
   - **Valorant Commands**:
     - Commands: `!rank`, `!crosshair`

### CSS Styles

- **General Styles**: 
  - Background gradient from orange to red.
  - Fonts and color schemes are chosen for readability and aesthetic appeal.
  
- **Responsive Design**: 
  - Styles adjust for devices with a maximum width of 768px to ensure usability on smaller screens.

- **Hover Effects**: 
  - Inputs and command items change background color on hover for better interactivity.

### JavaScript Functionality

- **Filtering by Group**: 
  - When a user selects a group from the dropdown, only the commands belonging to that group are displayed.

- **Search Functionality**: 
  - Users can type in the search box to filter commands based on their names or descriptions.

## Summary

This HTML page serves as a dynamic interface for Twitch commands, enabling users to easily find and filter commands based on their interests. The design focuses on a user-friendly experience with responsive elements and interactive features.
```
