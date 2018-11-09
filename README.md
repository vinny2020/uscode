This repository contains the complete United States Code.  Its purpose
is to publish the federal code in a way that makes it easy for
interested individuals to access both its content and its changes over
time.

Another purpose for this repository is to explore some ideas around
how to better facilitate the legislative process.  Legislation comes
in the form of bills which are essentially patches to the existing
legal code.  Many different versions of a patch may float around to be
debated, discussed, amended, etc., before a final version is applied
to the "trunk".  The process is extremely similar to how developers
manage software changes, particularly in the open source world.

I think it would be very cool if something like github were used to
manage the actual law, all in the open and fully visible to everyone.
I imagine the official code as sort of a master repository.  Each
legislator could fork this repository and hack on his own copy.
Legislators could pull from one another as they massage the language
to get it right.  The House and Senate would each have their own
forks, as would the committees.  The president, too would have a fork
of the official repository.

The legislative process would then be fully visible to anyone who
cares to look.  Congressman Blowhard commits a change to his code and
pushes it to the public fork.  Congressman Slick looks at it, likes
it, pulls, commits a change and tells Blowhard about his change, etc.
Eventually, the bill makes it to committee, and the committee may have
several branches indicating the status of bills as they progress
through the committee.  Eventually, if the bill is voted for
presentation to the House, it is pulled into the committee's "trunk".

If the House votes to approve the bill, then it's pulled to the
House's trunk, available to be pulled by the Senate.  The Senate can
make its own modifications, and perhaps the result must pass through a
House/Senate reconciliation committee, before being pushed to the
"Passed" branch (or fork), with a message to the president.

Anyway, that's the idea.  It may seem kind of silly, but if you've
ever actually tried to track the progress of a bill through the
existing web interfaces, it's horribly difficult, and there's a lot of
information about the bill's movement through the process that simply
isn't available.  I think using revision management tools just might
make the whole process both easier and more transparent. By tracking the 
origin and history of amendments, riders, and just bill authorship generally, 
it becomes easier to hold legislators accountable. 

And that's what I want to play with.
