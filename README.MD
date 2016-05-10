Introducing Meteor Toys 3, Because Toys Make Life Better
--------------------------------------------------------

They say whoever dies with the most toys is still dead. It’s true, but they still have the most toys. Still, sometimes it’s not about quantity as much as it is about quality, and sometimes, it’s about both. This Meteor Toys release, like all the others, is about giving you both. 

## I’m new to Meteor.. what are Meteor Toys?

Meteor Toys are the original development tools for the Meteor web development framework. They work with the classic stack of meteor-base, blaze/react, session, tracker and mongo to give you superpowers while developing. They cover everything from visualizing your client's data to helping you switch accounts in seconds, and more.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/MONGOL.gif">

The Meteor Toys packages sit quietly with-in your app, only to reveal their presence when you press Control + M. Normally, the functionality they provide could be seen as a security risk, but that is not a problem because they are marked as debugOnly. This means they only work when your app is in development mode, and Meteor will automatically remove them when you build for production.

Meteor Toys come in a free and premium edition, and are used by an estimate of thousands of Meteor developers. The premium customers range from college students and hobby developers to established businesses and government agencies. The common denominator I see is people who want to get to where they're going faster.

## Making All the Things Handier

Meteor Toys 2 were all about covering territory and focusing on extensibility with ToyKit and ThemeKit. With Meteor Toys 3, the focus shifted to improving the existing functionality and giving you the small changes that make the big differences.

For example, the Authenticate toy allows you to impersonate an account just by clicking on it. With the new update, the Toy will automatically detect the latest 15 accounts in your database, and you can also run a manual search with a username, email or _id. These features are especially handy when you’re using a seeded or cloned database. Additonally, when you impersonate an account while being signed into another, terminating the impersonation session will revert you to the previously authenticated account. It's too easy.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/ACCOUNTS.gif">

Meanwhile, the Pub and Method toy take it a step further from letting you visualize and run your publications and methods. Now, whenever you enter the arguments for them, Meteor Toys will automatically save them to localStorage. That way, you can easily tweak and re-run the functions as needed. When you run them, their results will be posted in the Result toy. The Result toy will also display the code you ran to get that result.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/METHOD.gif">

Throttle is one of my favorite toys because, well, they’re all my favorite. It's really nice at showing you how your application would feel in real life, where there is significantly more distance between the client, server and database compared to it all running on your laptop.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/THROTTLE.gif">

The new Throttle is even more reliable with support for two throttling speeds. Throttle works on DDP, while Chrome DevTools Throttle works on HTTP requests. Combine the two for a painfully honest development experience.

For the rest of changes and improvements, check out the changes on the Meteor Toys website.

## Introducing Meteor Toys Mobile

Meteor Toys have been dubbed “insanely handy,” but up until now, I’m afraid that label did not hold up for mobile development. Today, that changes with an interface optimized for mobile. It provides you access to commonly needed features: account impersonation, connection management, and reloading.

<img src="https://raw.githubusercontent.com/msavin/mtstory/master/MOBILE.png">

When Meteor Toys detect iPhone Mobile Safari or Cordova, they will load up the mobile interface instead of the desktop interface. This is completely optional with the `meteortoys:mobile` package.  This comes with a complementary `meteortoys:toggle` package which gives you a quick way to open the toys with your cursor instead of pressing Control + M.

## Meteor 1.3 and React Compatibility

Meteor Toys have improved compatibility with Meteor 1.3, and have been tested to work with the standard Meteor-Blaze and Meteor-React apps. While Meteor Toys continue to use Blaze for the view layer, they can easily accomodate people who prefer React.

Meteor-React and Meteor-Blaze share a lot of parts: minimongo, tracker, etc. In order to get Meteor Toys to work with Meteor-React, we only need to add on the Blaze library for rendering. It becomes included in development mode, and then removed along with Meteor Toys when you build for production.

## What Do We Do Next?

Meteor Toys are well integrated into the classic Meteor stack to make your development experience even more enjoyable. Virtually everyone who gave them a shot loves them, and the bugs that have been reported should be out of the way. Try them today and let me know they work for you, because there's nothing wrong with a a bit of play while you work!
