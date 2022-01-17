# Wordle2Townscaper

Wordle2Townscaper to is meant to translate Wordle tweets into Townscaper houses using yellow and green building blocks. You can download the tweet contents, parse pasted tweet contents or manually edit of 6 rows and 5 columns. Optionally, you can also choose whether wrong guesses should be left blank on Townscapper or filled with white blocks. Ground floor is always needed because you can change its color.

[![Screenshot](world2twitter.png)](https://twitter.com/tarmo888/status/1482938974809346049)
[![Screenshot](twitter2github.png)](https://tarmo888.github.io/Wordle2Townscaper/)
[![Screenshot](github2townscaper.jpg)](https://oskarstalberg.com/Townscaper/#FCIfEpiSPj0woaPjW9Mq2)

## Tech
This tool uses embedded tweet API to download (using proxy do avoid CORS) tweet contents, but that feature is optional. It can parse tweet contents pasted from mobile or desktop browsers, and it uses Townclipper library to build hashes for Townscaper. This tool can be hosted on static HTML hosting, like Github.io.

## License
MIT

## Thanks
* https://github.com/alvaro-cuesta/townsclipper
* https://github.com/tholman/github-corners
* https://github.com/twbs/bootstrap
* https://allorigins.win/