### Instructions: Local Setup

1. Clone this repository to your machine with `git clone <URL>`.
1. Execute `script/setup` from your command line. This ensures all the right dependencies are installed.
1. Execute `script/server` from your command line. This spins up a local instance of the project.
1. You can view the local instance by navigating to http://localhost:4000/

### Instructions: Add a Caption to an Existing Slide

1. Create a new branch with `git branch <UNIQUE-BRANCH-NAME>`.
1. Check out to your new branch with `git checkout <UNIQUE-BRANCH-NAME>`.
1. Open the slide you'd like to update from within the `_posts` folder. Use your favorite text editor.
1. Use [Markdown](https://guides.github.com/features/mastering-markdown/) to replace `Caption here` with your own caption. Leave any `{: .fragment}` blocks intact, as well as the front-matter content (lines 2-4) on the top of the page. Save your file.
1. Test your addition locally by refreshing http://localhost:4000/.
1. Stage your changes with `git add <FILE-NAME>`.
1. Commit your changes with `git commit -m "YOUR-COMMIT-MESSAGE"`.
1. Push your changes up to GitHub with `git push -u origin UNIQUE-BRANCH-NAME`.

### Instructions: Add a New Slide

1. Create a new branch with `git branch <UNIQUE-BRANCH-NAME>`.
1. Check out to your new branch with `git checkout <UNIQUE-BRANCH-NAME>`.
1. Save a new Markdown file in the `_posts` folder, with the naming convention: `####-##-##-title.md`, where the hashes indicate the position of the new slide in the deck.
1. Populate the slide with the template below and save.

        ---
        layout: slide
        title: "YOUR-TITLE-HERE"
        ---

        ![](IMAGE-URL-HERE)
        {: .center}

        Caption here
        {: .fragment}

        Caption here
        {: .fragment}

        Caption here
        {: .fragment}

        Caption here
        {: .fragment}

1. Test your addition locally by refreshing http://localhost:4000/.
1. Stage your changes with `git add <FILE-NAME>`.
1. Commit your changes with `git commit -m "YOUR-COMMIT-MESSAGE"`.
1. Push your changes up to GitHub with `git push -u origin UNIQUE-BRANCH-NAME`.
