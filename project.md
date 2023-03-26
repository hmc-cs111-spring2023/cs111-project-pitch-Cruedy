# Project proposal

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

_This language is catered towards users of Adobe's animation and video editing platforms who feel that the current language that is used for creating extensions to the platform is either too dificult to learn or that it isn't specific enough for the work they want to do. Currently javascript is the language used to create extensions or manipulate effects for Adobe software._

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

_There is currently a language used for this purpose, but it is a general purpose language, so I think a more specific language would be more appropriate. Since javascript isn't specfic to videos or animations, there is a lot of code required with javascript that I think could be avoided if a language specfic to videos was used._

### Why you?

_What excites you about this idea? How did you come up with it?_

_I've worked with Adobe After Effects, which is one of Adobe's video editing softwares, a lot, so I used javascript to work with its effects. I think Javascript doesn't work super poorly, but I think I could make a language that would make the process of manipulating effects even better._

### Domain

_Describe the project's domain in five words._

_Graphic, Video, Effects, Manipulation, Extension_

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

_The user isn't going to be writing large chunks of code for the most part, but is going to be using pre written methods to manipulate the effects. To create extensions and effects, the user would have to write more code. The editor is going to be in Adobe After Effects itself. I believe this is the right way to interact with the domain because this is how javascript is currently used with the software._

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

_The program will only run when a video with the effect that the program is changing. When the program runs, you'll see the change in the video. If there is an error in the program, the video frames will freeze and there will be an error message on the bottom of the video player screen._

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

_It should be easy to use expressions to manipulate effects. This basically means that it should be easy to call methods because that would be the main reason to use this language. It should also be easy to right a loop because looping an effect is necessary. It might be difficult to use cases and if statements because it's hard to use videos with cases._

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

_I don't think there are already DSLs in this domain because javascript is used for this and javascript is a general purpose language. Currently javascript does a fine job because you can call methods._

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

_I think most of the time would be spent on the language aspects of this project because there is already a system set in place for javascript, which is what is currently used in this domain. I think figuring out how to implement the language in this environment would be complicated._

### Scope

_How big an idea is this? How ambitious is this project?_

_I think this is a really ambitious porject because its a language that would have to work with an already complicated piece of software._

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_

_I think this is a good idea for a project because it would be helpful for a domain that I really enjoy working in. I think this may not be a good idea for a project because it seems  difficult to implement._
