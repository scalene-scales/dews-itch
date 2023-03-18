# Itch.io

This is the launch executable for DEW on `Itch.io`. While the game could be packaged and bundled as a single ZIP file, this may introduce unwarranted technical contraints, so an iframe approach is being used instead (also, setting up an iframe is cheap and easy).

Link to the game on `Itch.io`: [Click Here](https://scalene-scales.itch.io/de-waltz)

# Build

For some reason, uploading just an `index.html` file cause the game to never finish loading on `Itch.io`. So, run the following command for a release.

```
zip dew_for_itch.zip index.html
```
