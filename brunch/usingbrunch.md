Every web developer should have a few core skills that they need to understand. The core skill set? HTML, CSS, and Javascript. These markup, styling, and scripting languages rule the web, and will continue to rule for many years to come. If these technologies are so stable in their dominance, why then is web development such a rapidly changing industry? The answer lives deep within the psyche of every experienced internet "engineer." We all have a passion for creating modular, reusable code that can be hacked together into a great final product. The philosphy of recycling components and not having to write boilerplate for every single application isn't about being lazy, rather, it comes from the modern web-dev's ambition to create new and mind-blowing web experiences. Why waste time and money developing every application from scratch to often acheive a lower quality result? I'd rather focus on making my apps awesome for a lot less money and time by using build tools. Brunch (brunch.io) is one of these tools, and arguably the best out there in terms of simplicity, ease of use, and speed. Brunch compiles templates, styles, and scripts from your working directory, wraps them nicely inside of asynchronously loaded js modules (AMD) for faster website loading, and instantly pushes them into your build (public) directory. Along with this main functionality, Brunch also minifies scripts and optimizes static assets for limited bandwidth clients. It even includes a live-reload server that updates every time Brunch rebuilds your project, which is always, if you use `brunch watch --server`.  Deciding to use Brunch before anything else when planning your application will open up worlds of possibility, largely because it offers you the freedom to use literally any and all framworks that you may be accustomed to. 
As an example of how to effectively use Brunch to make life great for you and your clients, or mom, or uncle who desperately needs a web-app, I'm going to briefly walk you through building a site with this beauty! Here goes nothing! (Actually, everything.)

In order to demonstrate some concepts I'll be working on two projects in parallel, the only similarities between them being the developer (me), the MVC Framework (AngularJs), the style framwork (Bootstrap3), and potentially some shared components!

The first project will be for a friend of mine named Joe who owns a cleaning service in Orlando. In order to help him with business by injecting a steady stream of clients, we are going to create an app/site that allows for a few things to happen (excuse the free-flow psuedo here, just go with it):

1. Landing/About Joe's Service
2. User Login/Auth > Facebook or Simple Email
  2a. User is Client >  job request page.
  2b. User is Employee/Manager > response and admin pages.
3. Job Request > Create new request with user ID, Name, Phone, Address, Service Desired (One-time, Recurring, Commercial), Uploaded Pictures, Date/Time Desired.
4. Emp./Admin > Respond to service requests based on current location and availability, open payment terminal for accepting credit cards or cash on site.> Email Reciept > Payout to employees %, refund, etc...)
5. Thank You! Page
6. User Profile Page > Contains active request status, previously fulfilled requests with reciept records, reorder option.


So that's all I could squeeze out of my brain at the moment in terms of desired functionality for this app. While actively developing it, I might see room for more features, but at the moment these are the focus.



The second application is for another friend (I better start doing projects worth money). He wants a really clean, modern portfolio for his photography ventures, and has a really simple list of expectations...:

1. Wants to manage the content without much hassle or knowledge of code.
2. Wants to sell rights to use photos.
3. Wants a contact form that allows him to capture client email, phone, and project details.
4. Has a photography centric focus, leaving out the smalltalk and let the photos speak for themselves.

As for the site design (back to that mumbo jumbo mvc planning):

1. Landing > Random Project Album viewer (I'm thinking injecting photo stream as css background image with transition effects.)
2. Nav/Overlay > Select album/photo | contact form | About Me
3. Allow for login/auth to purchase licenses.
3a. If user is Client > Select License type > Payment terminal > Thanks! > User Dash to download full images and see reciepts.
3b. If user is admin (my friend) > create new albums + upload photos > respond to user > refund > etc.

Let's hope and pray that my ambition doesn't kill me, and with the help of these tools and frameworks I can accompish every last one of these goals!
