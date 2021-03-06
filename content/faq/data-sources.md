+++
date = "2016-08-01"
title = "Data Sources Questions"
original_url = "/faq/data-sources.html"

[menu.main]
    identifier = "faq_data-sources"
    name = "Data Sources Questions"
    parent = "faq"
    
+++
1.  <span class="underline"> What is the System Reference Document
    (SRD)? </span>

    It's basically a Open Gaming License subset of what's in the PHB,
    DMG, MM, Epic Level Handbook and the Psionics Handbook, the real
    difference being that what Wizards of the Coast has declared as
    Product Identity (PI) or Closed Content. That means the deities are
    not in there, some monsters, character names and places are omitted,
    and spell names may have been changed.

    See WotC's declaration what is not Open Content here: [SRD Legal
    Information](http://www.wizards.com/d20/files/v35/Legal.rtf)

    All non-SRD material (e.g. the splat books: Complete Warrior,
    Defenders of the Faith, Sword and Fist, Forgotten Realms, Dark
    Sun, etc. all TM of Wizards of the Coast) was handled by Code Monkey
    Publishing (see the next item).

2.  <span class="underline"> Why is book XYZ not included in PCGen?
    </span>

    There are a few possible causes for this situation and the
    explanation hold true for both datasets that have never been in
    PCGen and some which have been in PCGen but were removed.

    1.  If the book is closed content, then we may not have permission
        from the publisher, or may not have permission to include enough
        data to allow the data to be useful to our users.
    2.  If the book if partially or completely OGL content, then we
        still require permission from the publisher because the
        publisher name and book title are both trademarks. Under the
        OGL, we require permission to use those to identify the source
        of the data. We believe if we cannot identify the source of the
        data, then the value to PCGen users is lost (how do you find the
        data?), so we will not include a dataset for that source.
    3.  It is possible that PCGen does not have the features to support
        a sufficient amount of the data from a given source, and thus is
        not included in our production release (or is included as an
        alpha source)

    For more information on what sources are available in PCGen and
    explanations for those that are not, please refer to our Publisher
    Permissions page with this documentation set.

3.  <span class="underline"> Where are Wizards of the Coast's books and
    modules? </span>

    Those had been handled under a special license by the gang at [Code
    Monkey Publishing](http://www.codemonkeypublishing.com) (CMP).
    Sadly, late in 2006, WOTC declined to renew CMP's licence, and so
    they are no longer available for distribution.

4.  <span class="underline"> Where are the Star Wars/Call of
    Cthulhu/Wheel of Time files? </span>

    Even though Wizards of the Coast produces those books, they don't
    own exclusive rights to that material. We'll need to get permission
    from both Wizards and the other copyright owner(s) of said material
    before we can include them in PCGen. It is our intention to acquire
    this permission, but we're being very careful about how we proceed
    to maximize our chance of success. We'll keep everyone informed when
    anything worthy of reporting occurs. :)

5.  <span class="underline"> How do I include sources from Game Mode X
    in Game Mode Y that I currently use? </span>

    It is possible to do this, but you need to understand that this may
    cause errors due to incompatibility of the different Game Modes..

    To include all of Game Mode X's sources in Game Mode Y.

    1.  Go to the system/gamemode folder.
    2.  Choose the Y game mode folder.
    3.  Open miscinfo.lst.
    4.  Find the ALLOWEDMODES tag.
    5.  Append '|X' to this line.

    Now, all of the sources associated with Game Mode X will show up
    in Y. Remember you may experience problems while doing this.

    To include specific sources from game mode X in game mode Y.

    1.  Go to the \*.pcc of the game mode X source in question.
    2.  Find the GAMEMODE tag.
    3.  Open miscinfo.lst.
    4.  Append '|Y' to this line.
    5.  Repeat for every source wanted.

    Now, all of these specific sources from game mode X will show up
    in Y. Remember you may experience problems due to Game Mode
    incompatibilities while doing this.

------------------------------------------------------------------------



