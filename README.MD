Introducing Meteor Toys 3, Because Toys Make Life Better
--------------------------------------------------------

They say whoever dies with the most toys is still dead. It’s true, but they still have the most toys. Still, sometimes it’s not about quantity as much as it is about quality, and sometimes, it’s about both. This Meteor Toys release, like all the others, is about giving you both. 

## I’m new to Meteor.. what is Meteor Toys?

Meteor Toys is the original development tools for the Meteor web development framework. It works with the classic stack of meteor-base, templating (blaze/react), session, tracker and mongo to give you special powers during development. It covers everything from visualizing your client's data to helping you switch accounts in seconds, and more.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/MONGOL.gif">

The Meteor Toys packages sit quietly with-in your app, only to reveal their presence when you press Control + M. Normally, the functionality provided could be seen as a security risk, but that is not a problem because they are debugOnly packages. This means they only be included into your build when your app is in development mode.

Meteor Toys comes in a free and premium edition and is used by thousands of Meteor developers. Customers include everyone from college students and hobby developers to established businesses and government agencies. The common denominator between these different groups of people is that they all just want to get things done faster.

## Making All the Things Handier

Meteor Toys 2 was all about covering territory and focusing on customization with ToyKit and ThemeKit. With Meteor Toys 3, the focus shifted to improving the existing functionality and giving you the small changes that make the big differences.

For example, the Authenticate toy allows you to impersonate an account just by clicking on it. With the new update, the Toy will automatically detect the latest 15 accounts in your database, and you can also run a manual search. These two features are especially handy when you’re using a seeded or cloned database. Additonally, when you impersonate an account while being already signed in, terminating the impersonation session will revert you to the previously authenticated account. It's too easy.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/ACCOUNTS.gif">

Meanwhile, the Method and Pub Toys take it a step further from letting you visualize and run your methods and publications. Now, whenever you enter the arguments for them, Meteor Toys will automatically save them to localStorage. That way, you can easily tweak and re-run the functions as needed. When you run the Method or Shell Toys, their results will be posted in the Result Toy. The Result Toy will also display the code you ran to get that result.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/METHOD.gif">

Throttle is one of my favorite Toys because, well, they’re all my favorite. It's really nice at showing you how your application would feel in real life, where there is significantly more distance between the client, server and database compared to it all running from your laptop.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/THROTTLE.gif">

The new Throttle Toy is even more reliable with support for two throttling speeds. Meteor Toys Throttle works on DDP, while Chrome DevTools Throttle works on HTTP requests. Combine the two for a painfully honest development experience.

For the rest of the improvements, check out the changes in the Meteor Toys repository.

## Introducing Meteor Toys Mobile

Meteor Toys has been dubbed “insanely handy,” but up until now, I’m afraid that label did not hold up for mobile development. Today, that changes with an interface optimized for mobile devices. It provides you quick access to commonly needed features: account impersonation, connection management, and reloading.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/MOBILE.png">

When Meteor Toys detects iPhone Mobile Safari or Cordova, it will load up the mobile interface instead of the desktop interface. This is completely optional with the `meteortoys:mobile` package.  

Since Cordova may block your access to keyboard shortcuts, you can combine it with the new `meteortoys:toggle` package. The Meteor Toys Toggle gives you a quick way to open the Toys with a mouse hover or touch action.

## Meteor 1.3 and React Compatibility

Meteor Toys 3 has improved compatibility with Meteor 1.3, and has been tested to work with the standard Meteor-Blaze and Meteor-React apps. While Meteor Toys continue to use Blaze for the view layer, it can easily accommodate people who prefer React.

Meteor-React and Meteor-Blaze have many common parts: minimongo, tracker, etc. The main difference is the view layer. In order to get Meteor Toys to work with Meteor-React, we'd only need to add on the Blaze library. When you use Meteor Toys, it automatically gets included in development mode and then removed along with Meteor Toys when you build for production.

## What Do We Do Next?

Meteor Toys is well integrated into the classic Meteor stack to help you get things done faster and with more fun. Virtually everyone who gave Meteor Toys a shot loves it, and now it's your turn. Try Meteor Toys today and let me know how they work for you. There's nothing wrong with a a bit of play time while you work! 😎
