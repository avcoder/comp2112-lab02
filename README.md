# comp2112-lab2

### Purpose: Take an existing, static twitter-like HTML code, and make it dynamic via Javascript.

### What you'll need: 

* HTML framework for creating the twitter-like app - http://tachyons.io/components/lists/follower-notifications/index.html
* CSS that accompanies HTML framework 
```html 
<link rel="stylesheet" href="https://unpkg.com/tachyons@4.8.0/css/tachyons.min.css"/>
```
* Two arrays of objects:

```js
const heroes = [
  {'name' : 'Prof. Xavier', 'twitter' : '@profx', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0004.gif'},
  {'name' : 'Spiderman', 'twitter' : '@spidey', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0008.gif'},  
  {'name' : 'Wolverine', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0011.gif', 'twitter' : '@logan' }
];


const moreHeroes = [
   {'name' : 'Cyclops', 'twitter' : '@oneye', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0005.gif'},
   {'name' : 'Storm', 'twitter' : '@rainsitpours', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0007.gif'},
   {'name' : 'Phoenix', 'twitter' : '@jeangrey', 'pic' : 'http://www.animatedimages.org/data/media/450/animated-marvel-avatar-image-0016.gif'}
];
```

### Goals:
* Insert a button that will add an additional hero to the view; give a console warning if no more heroes.
* Make the 'Follow' button change to 'Following'upon being clicked, and vice versa; give console messages per click.
* 1 Bonus mark if you implement the new ES6 generator https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*#Examples
* 1 Bonus mark if you use the audio API https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement
  * can get sounds from https://notificationsounds.com/notification-sounds

Your lab2 should look/sound like this: https://youtu.be/D2N8d7NUF5k 

### To do (after you've coded the solution above):
* Upload your work to a new Private Github repository
* Invite me as a collaborator so I can see your repo
* Upload your work to Azure (or elsewhere, NOT codepen)

### Submit in Blackboard
* Your Github link to the above README.md file (ensure you've invited me as a collaborator)
* A hosted Azure (or other) url



