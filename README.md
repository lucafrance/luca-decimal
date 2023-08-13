# Luca Decimal Specification

This is the specification of *Luca-decimal*, the system I designed over time to organize my digital life.
It has been influenced by:
- [*Johnny Decimal*](https://johnnydecimal.com/), a system inspired by *Dewey Decimal*.
- [*Building a Second Brain*](https://www.buildingasecondbrain.com/), a note-taking system.

**Key principles**

- Acting is always preferred to not acting.
- Better to create more messier, than to create less orderly.

## Main structure

Start with the [four main folders of *Building a Second Brain*](https://fortelabs.com/blog/para/): *1 Projects*, *2 Areas*, *3 Resources*, *4 Archive*.
The purpose of each folder is based on the kind of action you are performing:

1. Something I am acting on for a limited time frame. → Projects
2. Something I am regularly acting on. → Areas
3. Something I am not acting on, but might be useful to act. → Resources
4. Something I am no longer acting on. → Archive

```
- 1 Projects
- 2 Areas
- 3 Resources
- 4 Archive
```

## Folder structure in *1 Projects*

Each folder in *1 Projects* has a prefix starting with 100 and increasing.

```
- 1 Projects
    - 100 Learn COBOL
    - 101 Taxes 2022
    - 102 Roof repair
- 2 Areas
    - ...
- 3 Resources
    - ...
- 4 Archive
    - ...
```

To add a new project, e.g. finding a birthday present for Johnny, you add a folder with the number prefix.
```
- 1 Projects
    - 100 Learn COBOL
    - 101 Taxes 2022
    - 102 Roof repair
    - 103 Birthday present for Johnny
- 2 Areas
    - ...
- 3 Resources
    - ...
- 4 Archive
    - ...
```

## Folder structure in *2 Areas* and *3 Resources*

Folders in *2 Areas* and *3 Resources* don't need to be numbered.
Some folders may be indexed with a prefix (201, 202, 203, ..., 301, 302, 303, ...) to "pin" them to the top when sorted alphabetically.
```
- 1 Projects
    - ...
- 2 Areas
    - 200 Health
    - 201 Finances
    - 202 Work
    - 203 Family pictures
    - ID documents
    - Travel card
    - Utilities bills
    - ...
- 3 Resources
    - 300 Books
    - 301 Comics
    - 302 Software
    - History documentaries
    - Instruction manuals
    - Mathematics
    - ...
- 4 Archive
    - ...
```

If used, the indexing logic in *2 Areas*, *3 Resources* is different than the one in *1 Projects*.
- In *1 Projects* the index sorts the folders by creation date.
- In *2 Areas*, *3 Resources* you define the order which makes the most sense to you.

## Folder structure in *4 Archive*

There is no naming restriction in *4 Archive*.
When archiving a folder, consider removing the index to avoid confusion.

E.g. project *117 Lorem Ipsum* is complete, you rename it to *Lorem Ipsum* and move it  to *4 Archive*.

Before:
```
- 1 Projects
    - ...
    - 117 Lorem Ipsum
    - ...
- 2 Areas
- 3 Resources
- 4 Archive
    - ...
```

After:
```
- 1 Projects
    - ...
- 2 Areas
- 3 Resources
- 4 Archive
    - ...
    - Lorem Ipsum
    - ...
```

## Subfolders indexing

You may decide to index subfolders (.01, .02, .03, ...) similarly to [*Jonny Decimal*'s IDs](https://johnnydecimal.com/concepts/ids/).
When in doubt, don't index.
If any other kind of naming convention makes more sense (e.g. by date), use it.

```
- 1 Projects
    - ...
- 2 Areas
    - 200 Health
        - ...
    - 201 Finances
        - 201.01 Bank account
        - 201.02 Savings account
        - 201.03 Credit cards
        - 201.04 Receipts
    - 202 Work
        - ...
    - 203 Family pictures
        - 2022
        - 2023
        - ...
    - ID documents
        - ...
    - Travel card
        - ...
    - Utilities bills
        - ...
    - ...
- 3 Resources
    - 300 Books
        - H.G. Wells
        - Umberto Eco
        - ...
    - 301 Comics
        - ...
    - 302 Software
        - 302.01 Operating systems
        - 302.02 Drivers
        - 302.03 Applications
    - History documentaries
        - ...
    - Instruction manuals
        - ...
    - Mathematics
        - ...
    - ...
- 4 Archive
    - Lorem Ipsum
        - ...
    - ...
```

## Consistency among different apps

Whichever structure and indexes are used, they must be kept consistent among all applications:

- local files,
- note taking apps,
- todo-apps.

There is no need to replicate the whole structure on each system constantly.
It is only necessary to ensure consistency once a topic is shared across multiple applications.

**Example**

- You have a folder in *2 Areas* called *201 Health*, where you save the pdfs of your exams results.
- You don't need a *Health* folder in your note taking and todo apps right away.
- If you add a reminder in your todo-app for a yearly check-up, then you should add it to a *201 Health* folder.
- If you add a note for the opening times of your doctor, it must also end up in a folder called *201 Health*.

Both [Johnny Decimal](https://johnnydecimal.com/concepts/keeping-notes) and [PARA](https://fortelabs.com/blog/para-setup-guide/) share a similar instruction.

## Links

- [Blog post about the logic behind the system](https://lucaf.eu/2023/02/23/luca-decimal.html)
- [Building a Second Brain](https://www.buildingasecondbrain.com/)
- [Johnny Decimal](https://johnnydecimal.com/)

## License

Copyright (c) 2023 Luca Franceschini (lucaf.eu)

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
