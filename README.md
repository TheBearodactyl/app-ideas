# A collection of app ideas to build and level up your coding skills

<p align="center">
   <img src="https://user-images.githubusercontent.com/34052076/200351617-af833e4e-6064-4d2f-b618-91c6f4a26296.svg" alt="logo" height="200">
</p>

## Material Design Theme + MudBlazor

- Generate as many as possible palettes based on your Primary/Secondary colors
- Generate palettes using palette generator: <https://coolors.co/account/general> , or similar one <https://mycolor.space/>
- Color theme creation
- Theming rules / methods: <https://m2.material.io/design/material-theming/implementing-your-theme.html#color>
- Add similar rules for creating custom theme: <https://m3.material.io/theme-builder#/dynamic> , or use the existing one
- Create, or use already exported css files that overrides MudBlazor theme
- MudBlazor is based on Material but some of the properties are missing, implement it by creating custom css, or components
- Create a custom component in MudBlazor that loads different themes/css, in order to visualize it
- Something similar or implemented on top of <https://github.com/MudBlazor/ThemeManager> that works directly with css bundles, so you don't need to manually click/select
- Bonus: Rules/Tool for creating Dark Theme or vice verse.. It probably already exists

## Database diagram visualizer for Entity Framework

- It automatically creates a database diagram image when there are new migrations
- by using reflection ?
- by using the designer file ?
- optionally add it as a github action and save it to the project dir, and add a reference to it in the readme file
- <https://github.com/azimuttapp/azimutt>

## Web API generator from JSON file

## Unit test generator

> A case analysis is performed for every conditional branch in the code. For example, if statements, assertions, and all operations that can throw exceptions are analyzed. This analysis is used to generate test data for a parameterized unit test for each of your methods, creating unit tests with high code coverage.

- <https://learn.microsoft.com/en-us/visualstudio/test/generate-unit-tests-for-your-code-with-intellitest?view=vs-2022>
- <https://github.com/cweill/gotests>
- <https://github.com/ed4becky/jest-unit-test-generator>

## Questionnaire

Create a dynamic questionnaire based on a list of questions provided

The structure of the questions are as follows:

- The questions are n-tiered and subsequent questions are asked based on the responses
    or series of responses of previous questions.
- In general, the questions are grouped, such that a set of questions are asked and that
determines if additional questions need to be added. Similar to the structure of a
treenode, where more questions are revealed if a node is clicked.
- The questions need to be asked one at a time
- The responses to the questions can be Boolean, radio selection (Boolean can fit here),
checkbox selection, checkbox selection with “other” textbox, or informational textbox.
- Each question is assigned a “point” value, and this needs to be recorded and reported to
tabulate a response
- from the Analyst – this point value is typically used to discretionary display further
questions depending on the value reported.
- The initial question (tier 0) is the acceptance of a disclaimer.
- There are domains for the sets of questions (aka categories) and this does not need to be
displayed

## Synonyms game

- <https://wordnet.princeton.edu/>
- <https://dictionaryapi.dev/>
- <https://developer.oxforddictionaries.com/documentation>

## Blazor WebAssembly game

- <https://github.com/amolenk/GameATron4000>
- <https://github.com/fernandreu/blazor-pages>

## Contribution graph pixel art

- Trigger a workflow
- Calculate a recurring event
- Push a commit
- <https://github.com/gelstudios/gitfiti>

## News feed profile readme

- Specify topics, keywords and time interval to trigger an action
- GitHub Actions
  - [Events that triggers workflows](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)
- Fetch and filter data
- Update profile readme

## Sports betting bot

- Sports Database
  - Types of Sports games
    - Football
      - club, league, country
      - club statistics: wins, losses, touches, own goals, yellow cards, red cards, goals,
      passes, shots, offsides, hit woodwork, big chances missed, tackles, clearances,
      clearances off line, dispossessed, clean sheets, saves, penalties saved, high claims, punches
      - season ?
      - players: club, nationality, position
      - player position: Goalkeeper, Defender, Midfielder, Forward
      - league player statistics: goals, assists, clean sheets, appearances, minutes played, yellow cards,
      passes, touches, shots, hit woodwork, big chances missed, tackles ( stats is saved by season for comparison )
  - Game results ( datetime, teams, score, odds )
  - Game rules for calculating winning conditions?

- Log In
  - by using Selenium or any other other tool
  - by using a list of user credentials for each website

- Data Scraping
  - odds from selected bookmakers
  - news about sports games
  - history for a game, player or any other related data

- Arbitrage
  - Checks betting odds for a certain event and automatically calculate whether an arbitrage bet is possible

- Some links
  - <https://en.wikipedia.org/wiki/Arbitrage_betting>
  - <https://github.com/georgedouzas/sports-betting>
  - <https://www.premierleague.com/stats/top/players/goals?se=489>
  - <https://data.world/datasets/sports>
  - <https://datahub.io/collections/football>

## Bytecode Compiler/Interpreter for Rust

- ByteCode Interpreter for rust
     - Have you ever been so bored out of your mind that you would do anything to not be?
       Well, no more! Now, you can rewrite the entire fucking rust compiler to use a
       bytecode interpreter instead of a compiler, and have it run on ANY device!
       Don't want to rewrite a compiler? too bad, now you're too invested in the idea to not!
       Have fun doing the near impossible!
