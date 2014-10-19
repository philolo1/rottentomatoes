## Rotten Tomatoes

This is a movies app displaying box office and top rental DVDs using the [Rotten Tomatoes API](http://developer.rottentomatoes.com/docs/read/JSON).

Time spent: 12 

### Features

  I tried a little bit with layout and it took me some time to get the details view working. I tried using taps for dvd and movies, but did not have time to figure out how to catch the click events.

#### Required

- [x] User can view a list of movies. Poster images load asynchronously.
- [x] User can view movie details by tapping on a cell.
- [x] User sees loading state while waiting for the API.
- [x] User sees error message when there is a network error: https://github.com/philolo1/rottentomatoes/blob/master/nework%20error.png 
- [x] User can pull to refresh the movie list.

#### Optional

- [ ] All images fade in.
- [x] For the larger poster, load the low-res first and switch to high-res when complete.
- [ ] All images should be cached in memory and disk: AppDelegate has an instance of `NSURLCache` and `NSURLRequest` makes a request with `NSURLRequestReturnCacheDataElseLoad` cache policy. I tested it by turning off wifi and restarting the app.
- [ ] Customize the highlight and selection effect of the cell.
- [ ] Customize the navigation bar.
- [ ] Add a tab bar for Box Office and DVD.
- [ ] Add a search bar: pretty simple implementation of searching against the existing table view data.

### Walkthrough
![Video Walkthrough](http://i.imgur.com/9d4fXIm.gif)

Credits
---------
* [Rotten Tomatoes API](http://developer.rottentomatoes.com/docs/read/JSON)
* [AFNetworking](https://github.com/AFNetworking/AFNetworking)










tasks completed:

* User can view a list of movies from Rotten Tomatoes. Poster images must be loading asynchronously.
* User can view movie details by tapping on a cell.
* User sees loading state while waiting for movies API. 
* User sees error message when there's a networking error. You may not use UIAlertView or a 3rd party library to display the error. See this screenshot for what the error message should look like: network error screenshot.
* User can pull to refresh the movie list. 
* optional: For the large poster, load the low-res image first, switch to high-res when complete

Notes: 
