# Zettelkasten on VSCode
This is my setup for my own knowledge system in VSCode. Feel free to modify it as you wish.

## Setup
- Clone this repository.
- Install recommended extensions. I originally used Foam, but found it to be optional, so use it as you wish.

## Methodology
Your capturing system lives in the `dump` folder.


## Fun Stuff I Included (feel free to remove it)
- `style.css`: Beautifies the Markdown Preview by highlighting H1 text with yellow. Change which CSS files to use for styling in `settings.json` as well.
- Code snippets
  - `ctime`: Gets the current time in HH:MM format
  - `tags`: Inserts a section that allows you to tag your note and link to other documents. Not necessary if you prefer inline linking/link-as-you-go
- "Macros" for Daily/Weekly notes
  - This is specified in `tasks.json`
  - To run the macro:
    - Open command palette (Cmd + Shift + P)
    - Select `Tasks: Run Tasks`
    - Choose the respective macro
  - **NOTE:**: You need to specify a default directory for the daily and weekly macros in `settings.json`

## Some stuff to keep in mind
- Use your system
- Use Git to your advantange!
- go by topics, not categories. use linking system, not folder categories
- Have fun!