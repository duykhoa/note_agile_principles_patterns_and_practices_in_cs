>>> Design and program are human activities; forget that and it lost

my expectation: fun, learn st from 2 genius people

ask for several user stories

for a story, ask for input/output

Assume the asker as a customer for this exercise, what form (interface) you want to input & output in

Use UML to describe

# Conclusion
"In preparing for battle I have always found that plans are useless, but planning is indispensable."

# More interesting parts (TL;DR)

- Well, if it doesn't have any behavior, how important can it be? I don't know if it exist or not yet.
I'd just feel more productive if we were working on an object that had more setters and getters for methods.
But if you want to drive...(give away the keyboard)

- Talk to me, Bob. The test is passing an integer, and the method expects a Throw object. You can't have it both ways.
Before you go down to the Throw path again, can you describe its behavior?

- Then I think we should do that for no other reason than it's simple. when we feel pain, we can do something more sophiscated

- I'm feeling kind of dumb because I can't visualize this. Show me some code.

- I don't know how to write the assertion, or maybe we're asking the wrong question. Or we're asking the right question but the wrong
object.

- Do you want to stop what we're doing on Frame and do a mental jump to Game, or do you just want to have a MockGame object that does
just what we need to get Frame working?

- I don't have that good of a memory, so let's make it more readable. But before we go screwing around with it some more, let's pull
code out of Add() and put it in a private member function called AdjustedCurrentFrame() or something.

- Maybe something will occur to us later. Right now, I think I see a bug. May I?

- Hmm, that doesn't fail. I thought since the twenty-first position of the array was a strike... But I guess not

- Hmm, you're still thinking about that scorer object aren't you. Anw, I see what you were getting at, but since score never calls Score
ForFrame with a number larger than 10, the last strike is not actually counted as a strike. It's just counted at a 10 to complete the
last spare. We never walk beyond the end of the array.

- OK, I'll trust you for a few steps, but remember, I'm watching

- Frankly, I don't know whether this is a good rule. It just what would have helped us in this case. So next time, I'm going to try it
and see what happens.

- Yeah, anw, we still have some refactoring to do.

- Ok, that looks pretty good. I can't think of anything else to do.

- Yeah, it's pretty. Let's look over the tess for good measure.

- That pretty much covers it. Can you think of any more meaningful test cases?

- No, I think that's the set. They aren't any there that I'd be comfortable removing at this point. 

- Then we're done.
