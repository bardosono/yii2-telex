Yii2-telex
==========

#### Telex news scroller widget for the Yii2 PHP Framework ####

Telex widget is a very lightweight widget to render my [Javascript telex widget](https://github.com/sjaakp/telex).

A demonstration of **Yii2-telex** is [here](http://www.sjaakpriester.nl/software/yii2-telex).

## Installation ##

Install **Yii2-telex** with [Composer](https://getcomposer.org/). Either add the following to the require section of your `composer.json` file:

`"sjaakp/yii2-telex": "*"` 

Or run:

`composer require sjaakp/yii2-telex "*"` 

You can manually install **Yii2-telex** by [downloading the source in ZIP-format](https://github.com/sjaakp/yii2-telex/archive/master.zip).

## Using Yii2-telex ##


#### options ####

Dateline has the following options:

- **messages**: array of messages. These are either `strings`, or `arrays` with the following members:
	- `content`: the text of the message. May also contain HTML, like a link.
	- `class` (*optional*): the CSS-class of the message. May be used for styling.
	- `id` (*optional*): the identifier of the message. For advanced use (see [telex widget](//sjaakpriester.nl/software/telex)).
- **options**: array of options for the underlying Javascript telex widget. More information [here](https://github.com/sjaakp/telex#messages "GitHub").
- **htmlOptions** (optional): array of HTML options for the Telex container. Use this if you want to explicitly set the ID. 
