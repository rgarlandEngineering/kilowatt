# quantum

MAY 5TH, 2022

Welcome everyone to the beginning of a project that will hopefully be a game changer. The objective of this project is to build a PUBLIC cross-platform application that helps users to shop for limited-release items. Shopping through our application should help normal users secure up to three items of their choice - whether it's three different items or three of the same item. For most web shops, most users are only allowed one item per limited release, however our goal is to ensure users of our platform will at least be able to secure one item, with a two-item buffer. This buffer will be accomplished by giving each user up to three chances per device to purchase the item.

Of course, there are questions: 

  - How will this application size up to major bot users whose aim is to acquire hundreds of pairs of sneakers? 
  - What if the user of the public application tries to find loopholes in the application to get more than three items?
  - What if the user of the public application has a slower/bad internet connection?
  - What if the user has an older system or device?
  - Will this application use standard/known bot technologies or newer api, http request techniques?
  
These are all questions that fuel the development process!

My theory,

We will be able to accomplish a clean checkout for our users by simply flowing with web stores. Most footsites and platforms are dynamically generating DOM elements classNames, IDs and such while running captcha puzzles. If we are able to build an api that seeks out particular elements, make them into JS objects, map them into Arrays, stringify them into JSON and send them back out as a payload utilizing functions that takes in user inputs as parameters, we should be successful with STILL filling in and clicking buttons based on their Selectors via automation. This is hard to ask, but I would love it if we didn't have to use known web scraping libraries. This will make our work, ten times easier to update when the time comes to adapt to new changes.

I will upload a diagram showing the methodology via PDF.
