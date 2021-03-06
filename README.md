# sweary <img src="sticker/sweary-sticker.png" align="right" width="150" />

Sweary is an R package that contains a database of swear words from different languages, cherry picked by native speakers.

## Installation

The development version of this package can be installed using [devtools](https://github.com/r-lib/devtools):

```
devtools::install_github("pdrhlik/sweary")
```

## Current swear word lists

| Language      | Language code | Number of swear words |
| ------------- | ------------- | --------------------- |
| Czech         | cs            | 57                    |
| English       | en            | 39                    |
| **Total**     | **2 langs**   | **96**                |

## How to use it

The package contains a data frame called `swear_words`. You can filter or modify it as you wish now. There will be convenient functions to extract only the languages that are of your interest.

## Contributions

You are welcome to create a pull request either with modifications to current lists or with a completely new language.

## Origin

The idea first appeared after the [South Park text analysis lightning talk](https://github.com/pdrhlik/southparktalk-whyr2018) at the [Why R? 2018 conference](http://whyr2018.pl/) in Wrocław. All the contributors will be acknowledged as the work progresses.
