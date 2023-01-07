# Prince of Unreal

An implementation of original "Prince of Persia" using Unreal engine... a story of failure.

The best way to learn something is doing something. I wanted to learn how to use Unreal engine 
to develop games and Prince of Persia is one of the best games ever. Besides that, that game is 
one of the latest classics of all times developed by a solo developer (well, I know that is not 
exactly true for the PC version but at is origins in Apple II it really is), so rebuild it just 
by myself was a realistic goal. Mechner published original source code some years ago and it 
has been remade in other development languages by other hobbyist developers, so I didn't expect 
any legal issues for recreating this game just for learning purposes as far I keep it free and 
open source.

Unreal engine is great but I felt they put the focus in 3D gaming while 2D developments was 
like a second class citizen. Its Blueprints system is brilliant, but I missed coding but the 
C++ alternative was not an alternative as I hate that language. Besides all those things, I 
made all possible mistakes a developer can do with a codebase: no functional tests, no cohesion, 
too much coupling, too much repeated code. 

You have to pay every sin and after nearly a year working in that project it was an spaghetti 
nightmare where I was spending more time finding and fixing regression errors than actually 
implementing the new functionality that caused those regression errors.

Finally, I decided to thrash that implementation and start it again from scratch using Unity.

Unity is far from being perfect, but I've found a better 2D support, an easier coding language (C#) 
I'm comfortable with and a a far more evident testing framework. With the lessons I had learned from 
my previous failure, after another year working in this attempt I feel happy with this new codebase. 
Everything in this life can be improved, but I feel honestly proud of this codebase. I've got very 
specialized components that are widely reused across the project (DRY), I know where is old code 
and where to put new code and I've developed a big collection of functional tests (130+) that make 
easy to detect and fix regression errors. I think an Unity new comer can learn many things studying 
my resulting codebase in that project.

I've really enjoyed my experience developing in Unity in contrast with my experience with Unreal.

**If you are interested in game development you'd better have a look to my [Unity version](https://github.com/dante-signal31/Prince_of_Unity).**

I'll keep this Unreal version here for those who like to learn from mistakes...but don't expect updates.
