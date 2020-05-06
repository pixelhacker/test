## iOS - Technical Assessment ##
This assessment is designed to evaluate the code organization, persistent data management, basic UI and models and unit tests. The duration is expected to be under 3 hours. Once complete, zip your Xcode project and send it back.


#### Expected behavior: ####
1 - Build two screens as shown above. The first screen shows a list of garment names and buttons to order the list by alphabetical order or by creation date/time.  A "+" button at the top right corner presents the second screen as a modal view.

The second screen allows saving a new garment in persistent memory, using the database of your choice. Tapping the “Save” button closes the modal view and returns to the first screen with the list. The list then shows the newly added garment.

2 - unit test some of the code

#### Developer Notes ####
Due to time constraints I choose to go with UserDefaults in order to save the user's garments. I kept the design clean and simple and I used preferredFonts as well as making the majority of the text localizable. I added a French localization text file so if you change your phone's Region/Language to French it will still work. I also made it work in dark mode as well.

I made use of some of the Extensions and CustomUI classes I use a lot, some have the prefix SFS, that's just the name I use for developing, Small Factory Studios.

Given more time I would have liked to have done the sorting functionality in a cleaner way. Currently it defaults to alphabetical (A-Z descending) and then by most recent if you switch to Creation Date.
