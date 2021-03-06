# Webring

This [webring](http://wiki.xxiivv.com/webring) is an attempt to inspire artists and developers to create and maintain their own website and share traffic among each other.

The webring's aim is to share personal websites such as diaries, wikis, bookmark lists, portfolios. To add yourself to the ring, submit a pull request to this repository. 

## Join the webring

Add your website url to the [index.html](https://github.com/XXIIVV/webring/edit/master/index.html), and add the webring icon to your website html. Alternatively, if you your website has a dark background, use `icon.white.svg`.

```
<a href='http://webring.xxiivv.com/' target='_blank'><img src='http://webring.xxiivv.com/icon.black.svg'/></a>
```

### Circular Linking

Instead of linking to the directory, you can also link to the next link in the ring by adding parts of your site or domain in the hash of the request url:

```
<a href='http://webring.xxiivv.com/#wiki.xxiivv' target='_blank'><img src='http://webring.xxiivv.com/icon.black.svg'/></a>
```

### Random Linking

Instead of linking to the directory, or to the next link, you can also decide to link to a random link from the directory by adding the hash `#random`: to the request url: 

```
<a href='http://webring.xxiivv.com/#random' target='_blank'><img src='http://webring.xxiivv.com/icon.black.svg'/></a>
```

## Need Help?

The ring master is [@neauoire](http://twitter.com/neauoire), but any member of the network is also welcome to join this repository as a collaborator to help manage new links and Pull Requests. Read more [here](http://wiki.xxiivv.com/webring).
