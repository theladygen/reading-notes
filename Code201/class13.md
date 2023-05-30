# Class 13

## Reading

### [Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

1.**Why would a developer use local storage for a web application?**

You need to store the state of your interface somewhere so it doesn't reset upon being closed and reopened. This is where local storage comes in. You would keep a key (like cookies) on the user’s computer and read it out when the user returns.

2.**What information should not be stored in local storage?**

There is the danger of people abusing it for darker purposes, exploiting all kinds of techniques, including local storage, to store information of a user on their computer even when cookies are turned off. This code could be used in all kinds of ways, and to date there is no way around it.

3.**Local storage can store what type of data? How would you convert it to that type before storing?**

One annoying shortcoming of local storage is that you can only store strings in the different keys. This means that when you have an object, it will not be stored the right way. You can work around this by using the native `JSON.stringify()` and `JSON.parse()` methods.

## Bookmark/Skim

[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

## Things I Want to Know More About

I would like to sandbox and experiment with all of this.

### ***Answers to questions were found researching and using the sources linked above each section***

[CF Reading Journal Home](../README.md)
