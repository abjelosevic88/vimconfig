# Welcome to my VIM configuration! :star2:

This configuration was forked from [ThePrimeagen](https://github.com/ThePrimeagen) configuration file. It was highly modified and a bunch of plugins was added in order to suit my personal preferences. A log of plugins were just custom text objects that I found useful in my coding sessions.

# Custom text objects

The folowing custom text objects were installed and some of the were forked and modified.

## Entire

This was used in order to target the whole document model:

 - `ae`/`ie` for the entire region of the current buffer

## Key/Value

This was used to target key/value paris like JavaScript object properties:

 - `ak`/`iv` for key / value

## XML attributes

This was used to target XML attributes:

 - `ax`/`ix` for XML/HTML attributes

## Chunk

This was forked and modified in order to change keystrokes. This was used in order to target all the lines contain one of {}, [], or () pairs:

 - `af`/`if` for all the lines contain one of {}, [], or () pairs, also `f` was mapped to go with commands like `df`, `cf` and `vf`

## Paragraph indend

This was used to target paragraf by indentation:

 - `ar`/`ir` for a paragraph with the same indentation / `g)`/`g(` for moving between paragraphs at the same indentation

## Punctuation

This was used to target next closest punctutation character: `,`, `.`, `:`, `;`, `!`, and `?`:

 - `au`/`iu` for the text between the cursor position and the closest punctuation in front, also works with `du`, `cu` and `vu`

## Quotes

This was used in order to target all quotes with a single keystroke:

 - `aq`/`iq` for the closest pairs of quotes of any type, also will work with `dq`, `cq` and `vq`

## Column

This was used to target column base selection:

 - `ac`/`ic`/`aC`/`iC` for columns of text defined by word or WORD

## Variable segment

This was also forked. It was used to target segments in camelCase and snake_case variables:

 - `as`/`is` for a region between either `_`s _or_ camelCaseVariables
