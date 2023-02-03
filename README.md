# Luca Decimal Specification

This is the specification of *Luca-decimal*, the system I designed over time to organize my digital life.
It has been influenced by [*Johnny Decimal*](https://johnnydecimal.com/), a system inspired by *Dewey Decimal*.
It is also influenced by [*Second Brain*](https://www.buildingasecondbrain.com/), a system designed for note-taking, but which can also be used for other purposes.

## Main structure

There are four main folders: *1 Projects*, *2 Areas*, *3 Resources*, *4 Archive*.
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

To add a new project, e.g. finding a birthday present dor John, you add a folder with the number prefix.
```
- 1 Projects
    - 100 Learn COBOL
    - 101 Taxes 2022
    - 102 Roof repair
    - 103 Birthday present for John
- 2 Areas
    - ...
- 3 Resources
    - ...
- 4 Archive
    - ...
```

## Folder structure in *2 Areas* and *3 Resources*

Folders in *Areas* and *Resources* don't need to be numbered.
Some or all may be numbered to "pin" them on the top.
```
- 1 Projects
- 2 Areas
    - 200 duohausdhs
    - 201 sdoihasu<odh
    - 202 sdhasudhaus
    - asuhausidhsau
    - buoadshsuai
    - cauiasuj
    - saydhasudh
- 3 Resources
    - 300 duohausdhs
    - 301 sdoihasu<odh
    - 302 sdhasudhaus
    - asuhausidhsau
    - buoadshsuai
    - cauiasuj
    - saydhasudh
- 4 Archive
```

## Folder structure in *4 Archive*

Folder numbering is free in *Archive*.
Probably a good idea to at least remove the number to avoid confusion.
E.g. project *117 Lorem Ipsum* is complete, you rename it to *Lorem Ipsum* and move it  to archive.

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

## Subfolders numbering

Additional level of numbering can be included *Jonny Decimal* style for numbered folders.
```
- 1 Projects
    - ...
- 2 Areas
    - ...
    - 221 sdhasudhaus
        - 202.01 idasuhd
        - 202.02 eujasidj
        - 202.03 dihasudha
    - ...
- 3 Resources
    - ...
    - 312 sdhasudhaus
        - 312.01 aoishad
        - 312.02 adhqoisjdwai
        - 312.03 asidhasudh
    - ...
- 4 Archive
    - ...
```

## Consistency among different apps

Consistency among systems.
All programs should follow the same structure.
- Local files.
- Note taking apps.
- Todo-apps

It doesn't need to be replicated everywhere all the time, but if anything related is across multiple programs it must stay consistent.
Example:
> You have an folder in *2 Areas* called *201 Health*, where you save the pdfs of your exams.
> You don't need *Health* in your note taking and todo apps right away.
> If you add a reminder in your todo-app for a yearly check-up, then you should also name it *Health*.
> If you add a note of the opening times of your doctor, it also must end up in a folder called *Health*.

TODO screenshot d'esempio
