# check_site for polybar

Simple polybar module for checking if a site is up using the is-up-cli a isitup.org cli api wrapper.
[sindresorhus](https://github.com/sindresorhus/is-up-cli)

## Screenshot
![Polybar Screenshot](/screenshots/screenshot.png?raw=true "Screenshot")

## Getting Started

### Dependencies

Arch Linux
```
$ yay -S is-up-cli
```

### Installing

* install is-up-cli
* add check_site.ini to the modules of your polybar
* copy check_site.sh into you scripts folder
* make check_site.sh executable
```
$ chmod +x check_site.sh
```
* edit check_site.sh to point to website you are wanting to check, you can also change the interval of how long between checks. 



## Authors

Jason Kingery
[@denialmedia](https://twitter.com/denialmedia)

## Version History
* 0.2
    * Added Screenshot

* 0.1
    * Initial Release

## License

This project is licensed under the [MIT License] License - see the LICENSE.md file for details

