# Zettelkasten on VSCode
This is my setup for my own knowledge system in VSCode. Feel free to modify it as you wish.

## Setup
- Clone this repository.
- Install recommended extensions. I originally used Foam, but found it to be optional (its features doesn't really enhance *my* experience, as of v0.8). So, it's entirely up to you!

## Methodology
- Your capturing system lives in the `dump` folder. This is where you store your "fleeting notes" - notes that you capture as the ideas pop into your head.
- Your long-term notes live in the `brain` folder. This is where you create links and connections between notes and build your second brain :)
- If you journal, you might find the `journal` folder useful to keep your `brain` clean

### Other principles & considerations
- Try to reduce the levels of folders that you have. Your notes should not be categorised into topics; rather, they should be linked together and searched through these links.
- I use Git for document versioning and you can consider doing that too :)

Others have used Foam to [publish these notes to the web](https://foambubble.github.io/foam/recipes/recipes#publish) (i.e. auto-deploy to GitHub Pages/Netlify/other platforms on `git push`). I'm not doing that here, as I prefer to keep my notes private.

@TODO I'll flesh out this section more as I delve deeper into the Zettelkasten methodology!

## Fun Stuff I Included (feel free to remove it)
- `style.css`: Beautifies the Markdown Preview by highlighting H1 text with yellow. Change which CSS files to use for styling in `settings.json`
- Code snippets
  - `ctime`: Gets the current time in HH:MM format
  - `tags`: Inserts a section that allows you to tag your note and link to other documents. Not necessary if you prefer inline linking/link-as-you-go
- "Macros" for Daily/Weekly notes
  - This is specified in `tasks.json`
  - To run the macro:
    1. Specify a default directory for the daily and weekly macros in `settings.json`
      - `notesMacro.weeklyDir` - For weekly notes
      - `notesMacro.dailyDir` - For daily notes
    2. Open command palette (Cmd + Shift + P) (Ctrl + Shift + P)
    3. Select `Tasks: Run Tasks`
    4. Choose the respective macro

Sometime in the future, I'll make it possible to create the weekly & daily notes with a template!

## If you have suggestions!
You can open an issue in this repository. I might not have the time to implement it, but I'll definitely take a look at what you've suggested!
