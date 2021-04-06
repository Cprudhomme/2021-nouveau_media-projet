# Markdown language

The markdown language has been created by John Gruber and Aaron Swartz to format text easily without needed to know HTML language.

## Formatting text

### Bold

The bolding of a text is done by putting the desired text between two stars or two underscores.

*Examples:*
````
  **Bold with stars** or __Bold with underscores__
````

*Results:*

**Bold with stars** or __Bold with underscores__

### Italic

The italicization of a text is done by putting the desired text between simple star or simple underscore.

*Examples:*
````
  *Italic with star* or _Italic with underscore_
````

*Results:*

*Italic with star* or _Italic with underscore_

## Structuring text


### Titles

The formatting of a title in markdown is done by using one or more sharps (depending on the level of your title) followed by a space, then your title.

*Examples:*
````
 # Titel level 1
 ## Titel level 2
 ### Titel level 3
 #### Titel level 4
````

*Results:*

  # Titel level 1
  ## Titel level 2
  ### Titel level 3
  #### Titel level 4

### Paragraphs

To create a paragraph, simply separate your text with an empty line.

*Examples:*
````
First paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam blandit ante vitae est fermentum malesuada. Mauris venenatis ac mauris at ornare. In iaculis felis nec neque elementum dapibus. Quisque sodales arcu id dictum dictum. Cras eu convallis neque. Nam tempus dictum arcu, sed iaculis libero fermentum eu. Nunc augue odio, suscipit ut pharetra sit amet, venenatis non velit. Donec consectetur ante ut nulla venenatis, eget interdum dui sollicitudin. Aenean gravida augue vel lectus malesuada tincidunt. Pellentesque lacus dui, malesuada iaculis tellus ac, sagittis varius libero. Suspendisse vestibulum, augue ut consectetur laoreet, lectus elit dignissim lorem, sit amet facilisis ipsum nulla non ligula. Sed tristique mi ut lorem faucibus commodo. Sed a molestie metus. Phasellus eget augue in ligula scelerisque cursus eu at felis. Sed odio urna, elementum vel tellus ut, egestas sodales nisl. Sed convallis finibus hendrerit.

Second paragraph: Quisque vulputate, massa ut egestas sagittis, urna dolor blandit arcu, ac cursus elit velit in nisi. Pellentesque massa sapien, auctor vitae ultrices id, facilisis iaculis odio. Vivamus a tincidunt dui. Donec vitae ex sed sem posuere iaculis. Ut vitae diam id massa maximus cursus. Sed id ligula eu ex viverra lacinia ut vitae mauris. Nullam ut elit ac magna placerat fermentum et vitae felis. Nullam aliquam mauris nibh, vel tempor mauris eleifend ut.
````

*Results:*

First paragraph: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam blandit ante vitae est fermentum malesuada. Mauris venenatis ac mauris at ornare. In iaculis felis nec neque elementum dapibus. Quisque sodales arcu id dictum dictum. Cras eu convallis neque. Nam tempus dictum arcu, sed iaculis libero fermentum eu. Nunc augue odio, suscipit ut pharetra sit amet, venenatis non velit. Donec consectetur ante ut nulla venenatis, eget interdum dui sollicitudin. Aenean gravida augue vel lectus malesuada tincidunt. Pellentesque lacus dui, malesuada iaculis tellus ac, sagittis varius libero. Suspendisse vestibulum, augue ut consectetur laoreet, lectus elit dignissim lorem, sit amet facilisis ipsum nulla non ligula. Sed tristique mi ut lorem faucibus commodo. Sed a molestie metus. Phasellus eget augue in ligula scelerisque cursus eu at felis. Sed odio urna, elementum vel tellus ut, egestas sodales nisl. Sed convallis finibus hendrerit.

Second paragraph: Quisque vulputate, massa ut egestas sagittis, urna dolor blandit arcu, ac cursus elit velit in nisi. Pellentesque massa sapien, auctor vitae ultrices id, facilisis iaculis odio. Vivamus a tincidunt dui. Donec vitae ex sed sem posuere iaculis. Ut vitae diam id massa maximus cursus. Sed id ligula eu ex viverra lacinia ut vitae mauris. Nullam ut elit ac magna placerat fermentum et vitae felis. Nullam aliquam mauris nibh, vel tempor mauris eleifend ut.

### Lists

#### Bulleted list:
Bulleted lists are created by using a star or a dash. To create a sub-list, precede the star or dash with an indentation level (i.e. one tab or 4 spaces).

*Examples:*
````
* Animals
    * Pets
        * Dog
        * Cat
        * Hamster
    * Farm animals
        * Cow
        * Hen
        * Goat

or

- Animals
    - Forest animals
        - Wild boar
        - Deer
    - Jungle animals
        - Monkey
        - Tiger
````

*Results:*

* Animals
    * Pets
        * Dog
        * Cat
        * Hamster
    * Farm animals
        * Cow
        * Hen
        * Goat

or

- Animals
    - Forest animals
        - Wild boar
        - Deer
    - Jungle animals
        - Monkey
        - Tiger

#### Numbered bulleted list:
Numbered bulleted lists are created by using a number, followed by a dot and a space.

*Examples:*
````
1. Coffee
2. Tea
3. Milk
````

*Results:*

1. Coffee
2. Tea
3. Milk

#### Mixed list:

*Examples:*
````
1. Breakfast
    - Coffee
    - Butter Croissant
    - Orange juice
2. Dinner
    * Raw vegetables
    * Chicken with chestnuts
    * Cheese
    * Dessert
````

*Results:*

1. Breakfast
    - Coffee
    - Butter Croissant
    - Orange juice
2. Dinner
    * Raw vegetables
    * Chicken with chestnuts
    * Cheese
    * Dessert

### Quote

A quote is made by preceding the text with a chevron, followed by a space.

*Examples:*
````
> "Whatever you are, be a good one." ― Abraham Lincoln
````

*Results:*

> "Whatever you are, be a good one." ― Abraham Lincoln

### Source code

To insert a source code, just indent it (4 spaces or a tab).
*Examples:*
````
    Example of code
````

*Results:*

    Example of code

To insert a code in a line, use a grave accent before and after your code.
*Examples:*
````
It is an example of code in line: `Example of code in line`.
````

*Results:*

It is an example of code in line: `Example of code in line`.

To insert uninterpreted Markdown code use 4 grave accents by going to the line, before and after your code.

### Table

*Examples:*
````
| Tables   |      Are      |  Cool |
|:----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |
````

*Results:*

| Tables   |      Are      |  Cool |
|:----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

## Including external sources


### Links

To create a link, place the link text in square brackets followed by the url in brackets.

*Examples:*
````
[John Gruber website](https://daringfireball.net/projects/markdown/)
````

*Results:*

[John Gruber website](https://daringfireball.net/projects/markdown/)

### Images


To insert an image, the principle is the same as for a link, except that you must add an exclamation mark before the brackets.

*Examples:*
````
![Flower image](/image/flower.jpg "Optional title: Flower image")
````

*Results:*

![Flower image](/image/flower.jpg "Optional title: Flower image")
