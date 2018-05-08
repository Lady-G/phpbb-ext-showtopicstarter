# PhpBB Extension - marttiphpbb Show Topic Starter

[Topic on phpBB.com](https://www.phpbb.com/community/viewtopic.php?f=456&t=2470526)

## Requirements

phpBB 3.2+ PHP 7+

## Features

This extension shows the string "Topic Starter" underneath the avatar in all posts of the topic starter (OP).

The original idea is from the [MOD Topic Starter](https://www.phpbb.com/customise/db/mod/topic_starter/).
Implemented as phpBB 3.2 extension.

## Screenshot

![Topic Starter](doc/topic_starter.png)

## Quick Install

You can install this on the latest release of phpBB 3.2 by following the steps below:

* Create `marttiphpbb/showtopicstarter` in the `ext` directory.
* Download and unpack the repository into `ext/marttiphpbb/showtopicstarter`
* Enable `Show Topic Starter` in the ACP at `Customise -> Manage extensions`.

## Customisation

You can customise the text description by modifying '/ext/marttiphpbb/showtopicstarter/language/en/common.php'
Replace 'Topic Starter' in the line 'MARTTIPHPBB_SHOWTOPICSTARTER_TOPIC_STARTER'	=> 'Topic Starter',' with your customised text.

You can customise the appearance by modifying the CSS file '/ext/marttiphpbb/showtopicstarter/styles/prosilver/theme/showtopicstarter.css'

Clear the system cache after the files have been modified. (ACP -> General -> Purge the cache)

## Uninstall

* Disable `Show Topic Starter` in the ACP at `Customise -> Extension Management -> Extensions`.
* To permanently uninstall, click `Delete Data`. Optionally delete the `/ext/marttiphpbb/showtopicstarter` directory.

## Support

* Report bugs and other issues to the [Issue Tracker](https://github.com/marttiphpbb/phpbb-ext-showtopicstarter/issues).

## License

[GPL-2.0](license.txt)
