# Faker

**Faker** (v. [0.0.0.2](http://hackage.haskell.org/package/faker)) is pure Haskell library for generating fake data.

```
  “It comes in very handy for taking screenshots (taking screenshots for my project,
  Catch the Best was the original impetus for the creation of this gem),
  having real-looking test data, and having your database populated with more
  than one or two records while you're doing development.”

                                              @stympy, creator of faker gem for Ruby
```

Inspired by:

* Ruby [faker](https://github.com/stympy/faker)
* Ruby [ffaker](https://github.com/EmmanuelOga/ffaker)
* PHP [Faker](https://github.com/fzaninotto/Faker)
* Python [faker](https://github.com/joke2k/Faker)
* Erlang [fakerl](https://github.com/mawuli-ypa/fakerl)
* Elixir [faker](https://github.com/igas/faker)
* Perl [faker](http://search.cpan.org/~jasonk/Data-Faker-0.07/)

# Install

```bash
cabal install faker
```

# Usage

```
:m Faker.Name

runFaker name -- => John Werbowsky
```

# Modules/Functions

* **Address**
  - [x] `buildingNumber`
  - [x] `city`
  - [x] `cityPrefix`
  - [x] `citySuffix`
  - [x] `country`
  - [x] `latitude`
  - [x] `longitude`
  - [x] `postcode`
  - [x] `secondaryAddress`
  - [x] `state`
  - [x] `stateAbbr`
  - [x] `streetAddress`
  - [x] `streetName`
  - [x] `streetSuffix`
  - [x] `timeZone`
* **Name**
  - [x] `firstName`
  - [x] `lastName`
  - [x] `name`
  - [x] `prefix`
  - [x] `suffix`
  - [x] `title`
* **Company**
  - [x] `name`
  - [x] `buzzwords`
  - [x] `bs`
  - [x] `suffix`
  - [x] `catchPhrase`
  - [x] `ein`
  - [x] `dunsNumber`
  - [x] `logo`
* **App**
  - [x] `name`
  - [x] `version`
  - [x] `author`
* **Business**
  - [x] `creditCardNumber`
  - [x] `creditCardExpiryDate` - TODO: should return date
  - [x] `creditCardType`
* **CreditCard**
  - [x] `visa`
  - [x] `mastercard`
  - [x] `discover`
  - [x] `discover`
  - [x] `americanExpress`
  - [x] `dinersClub`
  - [x] `jcb`
  - [x] `switch`
  - [x] `solo`
  - [x] `dankort`
  - [x] `maestro`
  - [x] `forbrugsforeningen`
  - [x] `laser`
* **Internet**
  - [x] `email`
  - [x] `safeEmail`
  - [x] `freeEmail`
  - [x] `generateEmail userName`
  - [x] `userName`
  - [x] `domainSuffix`
  - [x] `freeEmailDomain`
* **Hacker**
  - [x] `saySomethingSmart`
  - [x] `abbreviation`
  - [x] `adjective`
  - [x] `noun`
  - [x] `verb`
  - [x] `ingverb`
  - [x] `phrases`
* **Lorem**
  - [ ] `characters range -- (15,255)`
  - [x] `characters num`
  - [ ] `paragraph range -- (2,5)`
  - [x] `paragraph num`
  - [ ] `paragraphs range -- (2,5)`
  - [x] `paragraphs num`
  - [ ] `sentence range -- (4,10)`
  - [x] `sentence num mark`
  - [ ] `sentences range -- (2,5)`
  - [x] `sentences num`
  - [x] `word`
  - [ ] `sentences range -- (3,6)`
  - [x] `sentences num`
* **Avatar**
  - [x] `imageUrl`
  - [ ] `imageUrl slug`
  - [ ] `imageUrl width height`
  - [ ] `imageUrl slug width height`
* **Code**
  - [ ] `isbn`
  - [ ] `isbn10`
  - [ ] `isbn13`
  - [ ] `issn`
* **...**

# Thanks

[@igas](https://github.com/igas) for idea and explanation

# TODO

* Add rest modules and functions
* Improve performance
* Add haddoc documentation
* Use it with quickcheck
* Add translations

# Tools

Faker designed as lightweight library, because of it it can be easily used with
other tools.

## License

MIT License.
