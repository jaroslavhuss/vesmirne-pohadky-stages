# Vesmírné pohádky

## Releases and changelog

### 0.3.0

- 17.04.2024
- The mechanism behind source files download was completely changed. Now to user has full control over it. 
- Minor bug fixes
- IOS support (adhoc distribution)
- [ANDROID: Download Link here](https://drive.google.com/file/d/1gwS1EK4QWwHOcgj-3tCTZwapJUupK0bQ/view?usp=sharing)
- <a href="itms-services://?action=download-manifest&url=https://rgtests.cz/apps/pohadky-native.plist">IOS: Download here</a>

### 0.2.0

- 21.03.2024
- App accepts only minified pictures 400x400
- App does huge heavy lifting when working with sources - minimum calls to the server
- Bug fixes
- Update of settings - you can clear cache as well as local image memory
- [Download Link here](https://drive.google.com/file/d/17Nvx1wbUukgW4ale0UoDxz-LTrZFowRH/view?usp=sharing)

### 0.1.5

- 26.02.2024
- Admin panel - was removed, fuck that sh1t
- Removed dynamic loading with Async storage to prevent client from unwanted requests
- Added support to turn on/off images [defaul = true]
- [Download Link here](https://drive.google.com/file/d/1M73RX7_iFkUgH7QxRFH-2CopGLJ2zQ7J/view?usp=sharing)

### 0.1.4

- 26.02.2024
- Admin panel - flush fairytale data out of the device
- [Download Link here](https://drive.google.com/file/d/14_zyPdQ4rbJkHdPlccisRqLs6ZgCNwCT/view?usp=sharing)

### 0.1.3

- 25.02.2024
- Bug fixes (problem on foldable screens),
- Added descending sorting of any queries
- Added text-justification for better readability
- [Download Link here](https://drive.google.com/file/d/1TK1ArAswu8coxluAkk4VkmHQ2m756d1b/view?usp=drive_link)

### 0.1.2

- 23.02.2024
- Bug fixes, added theme suport for fairytales (light dark), added filtering based on author, category or label. Added setting screen for user to change the theme.
- [Download Link here](https://drive.google.com/file/d/1l-FTDnboaKJ3e-6QHoIoe8uWrwwLalfH/view?usp=sharing)

### 0.1.1

- 15.02.2024
- Inceremental updates to the app
- [Download Link here](https://drive.google.com/file/d/1zJN4F2fzuQHFC1uMJwlIJDjM9zjf-4bA/view?usp=drive_link)

### 0.1.0

- Date unknown
- Initial release
- [Download Link here](https://drive.google.com/file/d/1QJlUCBwTY-VKjMnQ8m43pm3-y_hf_u2r/view?usp=drive_link)

# TODO

- [x] Better req/res architecture for the app
- [x] Add more smart global state management to prevent req/res from being called multiple times
- [x] Add layer between CMS and app to prevent direct access to the CMS
