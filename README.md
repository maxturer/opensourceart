# OPEN SOURCE ART
[GW OSPO](https://github.com/gw-ospo)'s reusable open source [collaborative art piece](https://maxturer.github.io/opensourceart)

## HOW TO CONTRIBUTE ART
1. Make some art! That can be abstract patterns, self-portraits, botanicals, stick figures, photos, messages, and anything else you'd like to share. If you'd like to share something you've already made, that's fine too.
2. Take a photo of your work (your phone will work just fine)
3. Click on the button that says "Fork" to create your own copy of this repository.
4. Click on the `YOUR_PHOTOS_HERE` folder in the codebase, choose `Add File` in the top right corner, and upload your photo.
5. Click on "Pull requests" and then "New Pull Request"
6. As the "base repository", select `maxturer/opensourceart` and select `main` for the "base". As the "head repository", select "YOUR_USER_NAME/opensourceart" with `main` as the base. 
7. Open your pull request. Once we merge it, your art will join the collection. 

## HOW TO CONTRIBUTE CODE
This projection is a github pages site, brought to you by Jekyll and p5.js.
The fun stuff is in the `_includes` directory, particularly `Photo.js`, a class that handles animation and display of all the floating artwork.

To run locally, customize settings if needed in `_config.yml`, run `bundle install` to install ruby gems, and run `bundle exec jekyll serve` to launch in-browser.
