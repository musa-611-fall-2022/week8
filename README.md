# Introducing the Canvassing project

## Revisiting the Product Requirements Document (PRD)

> [Product Requirements Documents](https://github.com/musa-611-fall-2022/course-info/blob/main/resources/product-requirements-documents.md) in the course resources.

In the real world, the process of getting to a PRD may take several days to several weeks, and involve interviewing various stakeholders to really understand the problem that you're trying to solve.

The goal is to be able to form a hypothesis of what needs to be built.
- Start with who:
  - Best case scenario is that you're talking to the person you're building for -- the person that will be using the tool. Always try to do that.
  - Understanding who they are gives you context for the broad motivations of the person using the tool.
- Move on to why:
  - What are the goals that the person would like to achieve through the tool?
- Make a trip through how:
  - What is their process to get what they need to get done now? What's not working in that process?
  - Phrases that I like:
    - "This may be a stupid question, but..."
    - "Tell me about what you did yesterday/the last time you did..."
- Finally, take a crack at what:
  - Phrases that I like:
    - "If you had a magic wand and could make this tool do one thing..."

Compiling initial requirements is, in part, a process of converging mental models. You want to get to a point where you're reasonably confident that things that are in your stakeholders' heads are the same as the things in your head.

Recap from class:
* We interviewed me in order to understand what we were going to build for this project. We kept notes on that interview in [a document](https://docs.google.com/document/d/1jbbZi_qUqtLqOTgapmZ7r1Rsrqqvl_TEwOnCsW41L1M/edit?usp=sharing).
* We synthesized that information into a [collaboratively-developed PRD](https://github.com/musa-611-fall-2022/voter-canvassing/blob/main/PRD.md).

## Next time: Browser APIs

* API: Application Programming Interface
  * An "interface" is a way for two systems to communicate with each other. A "user interface" is a way for a user (system #1) to intereact with a program (system #2). An "application programming interface (API)" is a way for one program to interact with another program. A browser API is a way for your application to talk to various things that the browser provides for you. See below for some examples.
* [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) (redux)
  
  > The Fetch API provides an interface for fetching resources (including across the network). It ... provides a more powerful and flexible feature set [than previous built-in methods for fetching data].
* [Geolocation](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)

  > The Geolocation API allows the user to provide their location to web applications if they so desire.
* [Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

  > The Web Storage API provides mechanisms by which browsers can store key/value pairs, in a much more intuitive fashion than using cookies. `localStorage` ... persists even when the browser is closed and reopened.
* [History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API)

  > [The History API] exposes useful methods and properties that let you navigate back and forth through the user's history, and manipulate the contents of the history stack.