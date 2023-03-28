# The History of JavaScript

JavaScript is a high-level multi-paradigm programming language and it's under constant development and new features and improvements are always being added into JavaScript.

In 1995, websites were totally different from the ones that we use now. They were just plain text files mostly and people used an old web browser called `Netscape Navigator` to view these websites.

Netscape Navigator was the Google Chrome of it's time having more than 85% of the web browser market share. The founder of Netscape, Marc Andreessen wanted that the world wide web should be more than just simple text files.

He wanted to make websites dynamic and for achieving this Mark needed a programming language which could be used by both designers and developers.

For fulfilling this vision of his, Netscape hired a developer named Brendan Eich to add the `scheme` programming language into the Netscape Navigator.

Before Eich could complete his task Netscape joined `Sun Microsystems` to work on their new programming language called `Java`

Sun Microsystems wanted to make their new language available for web browsers and Netscape wanted a simple and easy scripting language that even designers can use but Java wasn't easy to learn.

Java wasn't the type of language that Netscape wanted and then they created a new language called `Moca.` Moca was later renamed to JavaScript because of the collaboration between Netscape and Sun Microsystems they decided that JavaScript and Java both should have a similar syntax.

# Microsoft and JavaScript

Brendan created the first version of JavaScript in just ten days. It had the object orientation of `Smalltalk` and the syntax of Java.

Microsoft began noticing the popularity of JavaScript since it was easy to learn and was getting more popular. Microsoft created their own version of JavaScript called `JScript` that only worked on `Internet Explorer`

JScript was same as JavaScript but had a slightly different way of implementing things. Which led to bigger problem than expected.Websites that were built using JavaScript worked best on Netscape Navigator and websites built with JScript worked best on Internet Explorer.

Developers had to add a best viewed in Internet Explorer/Netscape Navigator badges to their websites who couldn't build for both platforms.

# ECMAScript and the TC39

ECMA international is an industry association founded in 1961, which is dedicated to standardize the communication and information systems. In November 1996 Netscape handed over JavaScript to ECMA to build a standard implementation of the language.

This made the evolution of JavaScript easier and consistent across all vendors and implementors. ECMA is the governing body that standardizes JavaScript versions so that they are same across all web browsers.

Each new specification comes with a standard and a committee. JavaScript has the ECMA-262 standard and the committee which works on ECMA-262 is called TC39.

Oracle owns the trademark for the name JavaScript, so to avoid any legal issues ECMA calls JavaScript ECMAScript. The name ECMAScript is used for the official standard of the ECMA-262 while JavaScript is used while talking about the language in practice.

TC39 stands for technical committee-39. Which consists of members who are generally browser vendors or companies who have invested highly into the language, such as Facebook(Meta) and PayPal. Companies that are part of the TC39 send delegates who represents their companies at the TC39 meetings. These delegates are the ones who are responsible for creating, approving, or denying any feature that has been proposed to be added to the language.

Since 2016 ECMAScript has been releasing new features that have passed the criteria and adding them to the official spec. Each version is named with ES followed by the version number. ES6 was released in 2015 which added many new features to the language. Before 2015 the last update to ECMAScript was in 2011 which was called ES5.

# Adding new features to JavaScript

Whenever a member of the TC39 wants to add or improve a feature in JavaScript they have to submit a proposal to ECMA and the proposal is accepted only when it has gone through the five steps that determine that whether the feature should be added or not.

- **Stage Zero:** At this stage proposals are those that are planned to be presented to the committee or have not been rejected but do not meet the criteria to move to the next stage.
- **Stage One:** In order for any proposal to advance to stage one it must be presented by an official champion of the TC39 at the meeting who is responsible for the proposal and also define the problems it solves of the language and illustrative example along with a high level API example while also highlighting any potential concerns and implementation challenges.
- **Stage Two:** At the second stage, the proposed feature could become a part of the official spec of the language and the proposal should have an easy to read syntax and semantics of the feature in formal language. The proposal should also have a first version that is written in the official language specification.
- **Stage Three:**  Stage three is where the proposal is mostly finished and just requires feedback from the users and implementors, In order for a proposal to reach this stage the specifications of the proposal should be finished and implementations should be created.
- **Stage Four:** At the final stage the proposal is ready to be included into the specification of the language but requires complete written test about the proposal it should have two or more specification implementation should pass through those tests and the members have practical experience with the feature  and the ECMAScript editor must sign off on the specifications.
