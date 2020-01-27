# CPE 1040 - Spring 2020

## Assignment 3: Microbit Screensavers

This is the third assignment for the Spring 2020 installment of the CPE 1040 - Intro to Computer Engineering course at MSU Denver.

### Overview

This assignnment is more involved than the first two, but uses the same basic micro:bit functions. With some upfront design and several iterations of the implementation, it is within any student who has completed the previous two assignments. It asks you to create 5 "screensavers" for the micro:bit's 5x5 LED array (aka 25-LED matrix). The screensavers are moving patterns of lights that are displayed when the micro:bit is "put to sleep" and until it is "woken up".

### Requirements

#### 1. Modes

1. The program should have two modes, _asleep_ and _working_. It should do different things in the different modes.

2. Use a conditional (aka _boolean_) variable to track the mode.

3. In the _asleep_ mode, the micro:bit should show a "screensaver". In the _working_ mode, it should at least scroll a sentence of your choosing, or optionally do something more sophisticated.

#### 2. Controls

1. Use the A button to "put the screen to sleep" (that is, put the program in the _asleep_ state, activating the "screensaver").

2. Use the B button to "wake the screen up" (that is, put the program in the _working_ state).

3. **CHALLENGE:** Require that the A button is _held down_ for 2 seconds to activate the "screensaver", instead of just being pressed and released. _Hint: You need to use the `buttonIsPressed` and the timing functionality of the micro:bit._

#### 3. "Screensavers"

1. Design 5 abstract, randomized, moving patterns for the 5x5 LED array. Some ideas:
   1. Rotating "lines" like | / - \ | / -, that are centered at different spots.
   2. Dots that appear gradually and disappear gradually (use LED intensity), at random positions.
   3. Gradient waves, vertical, horizontal, or diagonal, where the parallel rows, columns, or diagonal lines change their intentsity in a wave-like manner.
   4. Concentric version of the gradient waves.
   5. **BONUS:** For the most original and unexpected "screensaver" pattern.
   
2. Make sure you can control which one is displayed. It's a good idea to wrap them in separate functions with descriptive names.

3. **BONUS:** Write a Screensaver class for the micro:bit.

4. The "screensaver" should time out and the "screen" should go blank. This does not automatically change the mode to _working_.

#### 4. Gestures

1. Pick 5 gestures to correspond to your 5 screensavers. When the micro:bit is _asleep_ and detects a gesture, it should switch to the corresponding "screensaver". This does not automatically change the mode to _working_.

2. The gestures should work _only_ when the "screensaver" is on (hat is, if the micro:bit is in the _working_ mode, the gestures should not do anything).

#### 5. Program versions

1. In the previous assignments, you only copy over your source code to your Github repository once, when you are done with the program. With larger programs, it is better to work in stages, and commit your current progress (usually, a partially completed program) to Github often. As Github is based on the version control system program Git (hence Github :)), you will have copies of all your different versions.

2. A suggested progression for the development of your program can be:
   1. Two different modes, changed by pressing buttons A and B. In this version, you can display two different icons to show in which mode you are.
   2. TODO

#### 6. README

1. Each time you design a new "screensaver", describe it in the [screensavers](#screensavers) section of the README.

#### 7. Demo video

1. Record a short video with your phone of your "screensavers" changing from gesture to gesture.

2. Upload it to [Imgur](https://help.imgur.com/hc/en-us/articles/115000083326-What-files-can-I-upload-What-is-the-size-limit-).

3. Include the URL in the [demo URL](#demo-url) section of the README.

## Resources

### micro:bit 

1. [micro:bit lessons](https://makecode.microbit.org/lessons).

2. [micro:bit ideas](https://microbit.org/ideas/).

3. A list of some more [advanced projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects).

4. The [projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects) at the [awesome micro:bit list](https://github.com/carlosperate/awesome-microbit).

### Github

1. Github Tutorial for Beginners ([webpage](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)).

2. Github Basics for Mac and Windows ([video](https://www.youtube.com/watch?v=0fKg7e37bQE)).

3. git & Github Crash Course for Beginners ([video](https://www.youtube.com/watch?v=SWYqp7iY_Tc)).

4. Introduction to Github for Beginners ([video](https://www.youtube.com/watch?v=fQLK8Ib_SKk)).

5. About `git` ([webpage](https://git-scm.com/about)).

6. `git` [documentation](https://git-scm.com/doc) (webpage, book, videos, reference manual).

7. [Github markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### JavaScript

1. Technically, the language which is used side-by-side with Blocks in the Makecode environment is a subset of [TypeScript](https://makecode.com/language), which itself is a superset of JavaScript (technically, [ECMAScript](https://www.ecma-international.org/ecma-262/10.0/index.html#Title)), with some JS features not implemented in Makecode.

2. The limited [JavaScript mini-tutorial](https://makecode.microbit.org/javascript) in Makecode. Make sure you read it but that can't be your only reference.

3. Official [TypeScript documentation]():
   1. TypeScript in 5 min [tutorial](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html). _**Highly recommended!** You will need to [download](https://www.typescriptlang.org/index.html#download-links) and install an integrated development envinronment (IDE). The two that I recommend are Visual Studio Code from Microsoft and WebStorm from JetBrains._
   2. The full documentation and reference is under _Handbook_. Bear in mind that you are drinking from the hose. Don't be surprised if not everything is presented in a strictly incremental manner.
   
4. In-browser TypeScript [playground](https://www.typescriptlang.org/play/index.html). Note that micro:bit specific code will not run, but you can still play. _Start making the distinction between a generic multi-purpose programming language (TypeScript) and functionality (packages, libraries, objects, etc.) that is specific to a particular device (micro:bit), though written in the same programming language._

5. A pretty good and very palatable JS tutorial with in-browser coding, by [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript).

6. Extensive and detailed [JS tutorial](https://javascript.info/), with some advanced material thrown in. _**I like this one!**

7. The most authoritative JS resource on the Web, including tutorials and reference, by [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

---

## Screensavers

### SS 1

_[Your description of screensaver 1]_

### SS 2 

_[And so on]_

## Demo URL

