# ngx-translate-quickcreate

<img src="https://res.cloudinary.com/teepublic/image/private/s--tKrGPgYa--/t_Resized%20Artwork/c_fit,g_north_west,h_954,w_954/co_262c3a,e_outline:48/co_262c3a,e_outline:inner_fill:48/co_ffffff,e_outline:48/co_ffffff,e_outline:inner_fill:48/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_jpg,h_630,q_90,w_630/v1489697662/production/designs/1330117_1.jpg" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="250" height="250"/>

This project contains VSCode extension `ngx-translate-quickcreate`.

## Requirements

For usage in an Angular project that uses [@ngx-translate](https://www.npmjs.com/package/@ngx-translate/core).

## Extension Commands

This extension contributes the following commands:

### Generate Translation String

Turns your selected text into a ngx-translate string and pipe.

#### Example Usage

1. Select word(s) that you want to translate
1. Open up the command palette (⇧⌘P (Windows, Linux Ctrl+Shift+P))
1. Search for `Translate: Generate Translation String`
1. Input a name you wish to refer to this value as, e.g. hello world
1. Selected text is now changed to the translation key with the pipe and translation copied to clipboard
1. Open your translations `.json` file and paste the clipboard contents

## Extension Settings

This extension contributes the following settings:

* `ngx-translate-quickcreate.replaceOnTranslate`: Replace the selected text after generating a translation string.
* `ngx-translate-quickcreate.translatePipeName`: The name of the pipe to handle the translation.
* `ngx-translate-quickcreate.quote`: Which quote to use around the inserted translation key.
* `ngx-translate-quickcreate.padding`: Add spaces inside the curly bracket pair.

## Release Notes

### 1.0.0

Initial release of `ngx-translate-quickcreate`
