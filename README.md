# R34

The goal of this project is to create a multi-platform application that centralizes your favorite R34 images and videos in one place. Available offline and secured with industry-standard security.

**Note:** This is an unpaid hobby project I do next to my full-time job. Progress will be very very slow and inconsistent.

### Latest builds

Cloud hosted builds & versioning coming soon.

## Tools used

### Unity 
For this project I'll be using the Unity Engine (2019.3.7f1) and design most of the codebase with MVVM in mind. It might be ported to Xamarin somewhere in time, but for now Unity provides a lot of stuff out-of-the-box.

## Roadmap

**0.1 alpha**
- [ ] Fullscreen image slideshow, hooked to a hard-coded danbooru api
- [ ] Storing links to favorite images / video
- [ ] password screen with disclaimers
- [ ] AES 128 encryption for local user data (Built-in RijndaelManaged)
- [ ] Build & test automation (Jenksins probably)
- [ ] Windows standalone support

**0.2 beta**
- [ ] Code standards document + the necessary code refactors
- [ ] Technical chart of the main systems & their dependencies
- [ ] Gallery viewer (multiple images with automated layout)
- [ ] Automatic scrolling for fullscreen viewer
- [ ] Switching backend to different imageboards
- [ ] Android support (8.0 and higher)

**0.3 release candidate**
- [ ] General UI styling & visual fluff
- [ ] SFX on clicks, menus, etc
- [ ] First pass on Performance optimisation
- [ ] Some form of Analytics & crash reporting
- [ ] Credits, options, etc

**Vague future ideas**
- New posts screen, with images containing favorited tags
- Suggestions based on favorited posts & tags
- 'Vault-like' storage, making bigger chunks of data instead of individually offline encrypted files


## Authors

* **DZDB** - Programmer - [Github](https://github.com/DZDB)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Disclaimer

* This is project is not affiliated with any danbooru site.
* This is my personal project without any sponsors, and I will not accept any donations of any kind.