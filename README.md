# URL Shortener Tech Test

Life is way too short to type out entire URLs. No-one on the internet has ever
come up with a sane way of shortening URLs, especially not bit.ly, goo.gl or
anything similar. Therefore, we want you to build your very own URL shortener
and disrupt this 10x growth market.

## Specification

We often have links that looks like this:

`https://github.com/makersacademy/jobhunters/blob/master/Finding%20and%20Applying%20for%20Jobs/keeping_it_fun.md`

What we really want is a link that looks like this:

`https://spike.ly/P5HrXO`

## Version 1

* Create a web application with form that takes a long URL and generates a short 
  URL, storing the short URL and long URL together in a persistant data store.
* The application should redirect users to the long URL when the short URL is visited
* Users should not be able to submit an invalid URL
* The application should check if the URL has already been stored and not
  create duplicate entries

## Version 2

* Style the application - use a site like [bit.ly](https://bit.ly) as an
  inspiration, or come up with your own design.

## Verson 3

* Track the number of times a shortened URL has been visited
* Track the time and date that a shortened URL has been visited
* Create a statistics page, for example at `https://spike.ly/P5HrXO/stats`,
  that shows the short URL, the long URL, each visit and the total number of
  visits

You may use whatever technologies you see fit. Try to be deployed as early as
possible.
