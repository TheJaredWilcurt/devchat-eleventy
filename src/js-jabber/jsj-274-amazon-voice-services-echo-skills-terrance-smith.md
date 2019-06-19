---
layout: layouts/post.njk
title: >
  JSJ 274 Amazon Voice Services and Echo Skills with Terrance Smith
date: 2017-08-15 04:00:21
episode_number: 274
duration: 49:37
audio_url: https://media.devchat.tv//js-jabber/JSJ_274_Amazon_Voice_Services_and_Echo_Skills_with_Terrance_Smith.mp3
podcast: js-jabber
tags:
  - js_jabber
  - podcast
---

## **JSJ 274 Amazon Voice Services and Echo Skills with Terrance Smith**

On today’s episode of JavaScript Jabber, we have panelists Joe Eames, Aimee Knight, Charles Max Wood, and we have special guest Terrance Smith. He’s here today to talk about the Amazon Alexa platform. So tune in and learn more about Amazon Voice Services!**[01:00] – Introduction to Terrance Smith**Terrance is from Hacker Ferrer Software. They hack love into software.**[01:30] – Amazon Voice Service**What I’m working on is called My CareTaker named probably pending change. What it will do and what it is doing will be to help you be there as a caretaker’s aid for the person in your life. If you have to take care an older parent, My CareTaker will be there in your place if you have to work that day. It will be your liaison to that person. Your mom and dad can talk to My CareTaker and My CareTaker could signal you via SMS or email message or tweet, anything on your usage dashboard, and you would be able to respond. It’s there when you’re not.**[04:35] – Capabilities** Getting started with it, there are different layers. The first layer is the Skills Kit for generally getting into the Amazon IoT. It has a limited subset of the functionality. You can give commands. The device parses them, sends them to Amazon’s endpoint, Amazon sends a call back to your API endpoint, and you can do whatever you want. That is the first level. You can make it do things like turn on your light switch, start your car, change your thermostat, or make an API call to some website somewhere to do anything.**[05:50] – Skills Kit**Skills Kit is different with AVS. Skills Kit, you can install it on any device. You’re spinning up a web service and register it on Amazon’s website. As long as you have an endpoint, you can register, say, the Amazon Web Services Lambda. Start that up and do something. The Skills Kit is literally the web endpoint response. Amazon Voice Services is a bit more in-depth.**[07:00] – Steps for programming**With the Skills Kit, you register what would be your utterance, your skill name, and you would give it a couple of sets of phrases to accept. Say, you have a skill that can start a car, your skill is “Car Starter.” “Alexa tell Car Starter to start the car.” At which point, your web service will be notified that that is the utterance. It literally has a case statement. You can have any number of individual conditional branches outside of that. The limitation for the Skills Kit is you have to have the “tell” or “ask” and the name of the skill to do whatever. It’s also going to be publicly accessible. For the most part, it’s literally a web service.**[10:55] – Boilerplates for AWS Lambda**Boilerplates can be used if you want to develop for production. If you publish a skill, you get free AVS instance time. You can host your skill for free for some amount of time. There are GUI tools to make it easier but if you’re a developer, you’re probably going to do the spin up a web service and deal it that way.**[11:45] – Do you have to have an Amazon Echo?**At one point, you have to have the Echo but now there is this called Echoism, which allows you to run it in your browser. In addition to that, you can potentially install it on a device like a Raspberry Pi and run Amazon Voice Services. The actual engine is on your PC, Mac, or Linux box. You have different options.**[12:35] – Machine learning**There are certain things that Amazon Alexa understand now that it did last year or time before that like understanding utterances and phrases better. A lot of the machine learning is definitely under the covers. The other portion of it Alexa Voice Service, which is a whole engine that you have untethered access to other portions like how to handle responses. That’s where you can build a custom device and take it apart. So the API that we’re working with here is just using JSON and HTTP.**[16:40] – Amazon Echo Show**You have that full real-time back and forth communication ability but there is no video streaming or video processing ability yet. You can utilize the engine in such a way that Amazon Voice Services can work with your existing tool language. If you have a Raspberry Pi and you have a camera to it, you can potentially work within that. But again, the official API’s and docs for that are not available yet.**[27:20] – Challenges**There’s an appliance in this house that listens to everything I say. There’s that natural inclination to not trust it, especially with the older generations. Giving past that is getting people to use the device. Some of the programming sides of it are getting the communication to work, doing something that Alexa isn’t pre-programmed to do. There isn’t a lot of documentation out there, just a couple of examples. The original examples are written in Java and trying to convert it to Node or JavaScript would be some of the technical challenges. In addition, getting it installed and setup takes at least an hour at the beginning. There’s also a learning curve involved.**[29:35] – Is your product layered in an Echo or is your product a separate device?**Terrance’s product is a completely separate device. One of the functionality of his program is medicine reminders. It can only respond to whatever the API calls from Amazon tells you to respond to but it can’t do anything like send something back. It can do an immediate audio response with a picture or turn on and off a light switch. But it can’t send a message back in like two hours from now. You do want your Alexa device to have (verbally) a list of notifications like on your phone. TLDR, Terrance can go a little further with just the Skills Kit.**[32:00] – Could you set it up through a web server?**Yes. There are examples out there. There’s Alexa in the browser. You can open up a browser and communicate with that. There are examples of it being installed like an app. You can deploy it to your existing iPhone app or Android app and have it interact that way. Or you can have it interact independently on a completely different device like a Raspberry Pi. But not a lot of folks are using it that way.**[33:10] – Monetization**Amazon isn’t changing anything in terms of monetization. They make discovery a lot easier though. If you knew the name of the app, you could just say, “Alexa, [tell the name of the app].” It will do a lazy load of the actual skill and it will add it to your available skill’s list. However, there is something called the Alexa Fund, which is kind of a startup fund that they have, which you can apply for. If you’re doing something interesting, there is a number of things you have to do. Ideally, you can get funding for whatever your product is. It is an available avenue for you.**[36:25] – More information, documentation, walkthroughs**The number one place to go to as far as getting started is the Amazon websites. They have the Conexant 4-Mic Far-Field Dev Kit. It has 4 mics and it has already a lot of what you need. You have to boot it up and/or SSH into it or plug it up and code it. They have a couple of these kits for $300 to $400. It’s one of the safe and simpler options. There are also directions for the AVS sites which is under Alexa Voice Services, where you can go to the Github from there. There will give you directions using the Raspberry Pi. &nbsp;If not that, there’s also the Slack chatroom. It is [alexaslack.com](https://alexaslack.com). Travis Teague is the guy in charge in there. **Picks\*\*** Joe Eames\*\*

- [Cosmic Engineers by Clifford D. Simak](https://www.amazon.com/Cosmic-Engineers-Clifford-D-Simak/dp/041705730X)
  **Aimee Knight**
- [Conference: React Rally](https://www.reactrally.com/)
- Pancakes
  **Charles Max Wood**
- [Conference: Angular Dev Summit](https://angularsummit.com/)
- Conference: React Dev Summit
- [JavaScript Jabber Slack](https://devchat.tv/register/javascript-jabber-slack)
  **Terrance Smith**
- [Language: Elm](https://elm-lang.org/)
- [Youtube channel: The School of Life](https://www.youtube.com/user/schooloflifechannel)
- [Game: Night in the Woods](https://www.nightinthewoods.com/)
- [Hacker Ferret Software](https://hackerferret.com/)
- [Hackerferret.com](https://hackerferret.com/)

### Transcript