POSSIBLE TOPICS
==============
Color Blindness - bonus - ZOMG I'M TOTALLY DOING IT NOW FOR SURE B/C I GET TO TALK ABOUT BORDERLANDS 2!!!
Screen Readers - overview... mention more popular ones, demo JAWS
???
Profit!!


Intro
-----
Who I am
How I got roped into doing a talk over Accessibility
Who I pinged to get my info
Where to get my notes, slides etc for this talk - file github issues with questions or feedback etc.

Accessibility Stats
-------------------
ESTIMATED

% of population with low or no vision
    6.6 mil Americans
285 million people are estimated to be visually impaired worldwide: 39 million are blind and 246 have low vision.
About 90% of the world's visually impaired live in low-income settings.
    6.6 Mil Americans blind/low-vision
5% of population with disabling hearing loss
    360 million
    43 Mil Americans
    Current production of hearing aids meets less than 10% of global need.
    ~10% of population estimated to have some degree of hearing loss
% of population who have varying degrees of color blindness

Reasons for developing with Accessibility in mind
-------------------------------------------------
Good Reason: 
    Time spent by a developer towards _minimal_ accessibility boosts translates to _major_ time savings by any user with vision or hearing impairment.
    The more devs exercise accessibility tools, the more feedback and improvements will be made, thus improving experiences for both devs as well as users.

A-hole Reason:
    Government agencies require 508 compliance, so developing software with 508 in mind makes your product usable by a broader audience...  like, hypothetically ... gov't agencies ... which might have a lot of hypothetical tax dollars to spend.  So it would basically help you get your own money back ;)
    Better search results, overlab with other best practices

Tools for people with vision loss
---------------------------------
Screen Readers
    Usually just for Windows.
        NVDA - free ... super chatty - rising in popularity
        JAWS - $UPER NOT FREE - more popular _for now_
    
Braille Displays - UH. $PENSIVES. https://www.google.com/search?q=braille+display&oq=braille+display#q=braille+display&tbm=shop
    Not just for Wx - https://www.apple.com/accessibility/ios/braille-display.html 
    I have no idea how they work
Mobile app Sharaine's dad uses - ZoomText on iPhone - magnification etc

Tools for people with hearing loss
----------------------------------
Captioning
    Auto-captioning frequently terrible, unusable, unGUESSable http://youtu.be/XArx0ASwyDc?t=46s
    Sites Sharaine linked for manual captioning
        self-captioning service - www.amara.com
        professional service - www.captionfirst.com

Tools for people with color-blindness
-------------------------------------
Colorblind Assistant http://www.littlesky.org/?q=apps
I honestly don't know what else

Vision - DEMO NVDA - OMG IT'S INSANE!!!
------------------------------

Vision - DEMO JAWS
------------------
Google "Twitter dev_ict"
Find and inspect element on an X close button or something - note aria crap - maybe later?

Hearing - YOUTUBE DEMO
----------------------
http://youtu.be/XArx0ASwyDc?t=46s
See how amazing and beautiful?

Color Blindness
---------------
Link and skim Broderlanz 2 article
http://www.gearboxsoftware.com/community/articles/1128/inside-the-box-adding-a-colorblind-mode-to-borderlands-2

Demo Chrome Plugin on NewEgg site or better yet http://www.daltonize.org/ and http://www.merry-christmas.com/

Color Contrast tool from WebAim

WHAT CAN BE DONE!?
------------------

Vision
------
W/o aria or screen-reader specific classes etc
    Don't forget alt text
    Avoid improper (all?) use of Flash elements ;)
    Avoid improperly labelled forms

Squiz Codesniffer - can be configured to check for 508 compliance ... ish :D
Navigation
    Make sure you can traverse using tab, arrow keys, escape, enter, space etc
    If a dialog claims focus, it should return focus to launch point after completion

aria-label and aria-hidden
    do you want a person to know you have ASCII art of an Xzibit meme, or do you want the screen reader to try and read the ASCII?

aria landmarks
    effectively navigate to various locations at the beginning of major content sections


