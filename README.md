# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Gina De La Guardia

_Student NetID_: gyd1

## Problem 1
- Scenario: {Grading}
- Assumptions:
  - Only one assignment submission (the most recent submission) is being graded per student.
  - All students are assigned the same homework.
  - Grades are kept in an online electronic system (like canvas).
  - No late submissions allowed.
- Assets:
  - Grades: Students and external parties cannot change the grades in the system (integrity). Students can only see their own grades, and not other students' grades, but the professors and staff can see everyone's grades (confidentiality).
  - Timestamp of assignment submission: This is important because the professors must be able to confirm that a student turned an assignment in on time. So the timestamp should not be modifiable, and should only be set automatically by the computer clock.
  - Solutions: Whether or not students can view the solutions is in control of the professors and staff, meaning the staff can keep the solutions private until after the homework due date.
  - Assignment Submissions: Students should not be able to view or modify other student's assignments that have been submitted, only their own. And they should not be allowed to modify their assignments after the deadline has passed.
- Threats:
  - Students modifying their own grades.
  - Students modifying their submission content, submission timestamp, and/or submitting after the deadline.
  - Studetns viewing/modifying other students' assignments.
  - Students viewing/modifying other students' grades.
  - Students viewing the solutions before the assignment due date.
  - People outside of the class accessing this course content. 
- Countermeasures:
  - Only professors and staff (e.g. TA's) have a login account for the grades page.
  - Log activity of grades page activity and student desktop logins (perhaps they correspond when a student attempts to change his/her grade). 
  - Save grades in two places, that way if they are modified in one location, you can detect it if there is a difference between the two locations. Have this updated periodically. Also this second location could be stored locally in a locked office where only professors and staff have physical access.
  - Have the solutions password protected, and have a checker that compares solutions with student submissions and checks for plagiarizing. 
  - Have the assignments turned in in a format where the timestamp is recorded with the submission and that submission may not be edited. However resubmissions are allowed (with their new corresponding timestamp). Also have some sort of timestamp verification process. 
  - Log activity of logins to the course page, including student ID's with some sort of verification that the students are enrolled in the course. 

## Problem 2
- Scenario: {Stadium}
- Assumptions:
  - Football stadium is of standard size.
  - Stadium is not used for activities/events other than football practice and games.
  - No assigned seats.
  - Can only enter stadium with a ticket.
- Assets:
  - Entry into the stadium. This is limited to people with tickets or players / cheerleaders / hosts & commentators / concession stand runners.
  - Scoreboard and sound system (and any sort of visual or audio display for the players and audience). This has to be controlled only by the commentators and others behind the soundbooth in charge of it.
  - Equipment ( both for team and for the field). Must be protected from theft and damage.
  - Locker rooms / offices are private spaces and may contain important items, information, and people.
  - Football Players / Cheerleaders / Other people on the field (who should be on the field).
  - Stadium attendees / fans should be kept safe throughout their time at the stadium.
- Threats:
  - Modification of the scoreboard by someone other than the score keepers.
  - Hacking into the sound system to project sound other than the intended (game commentators, etc).
  - People sneaking into the stadium without a ticket.
  - Theft of player equipment, tickets, any personal items, or concession items (including concession money).
  - Violence, including fights or even weapons.
- Countermeasures:
  - Have guards at all the entrances and exits of the stadium, checking the ticket as well as the ticket holder's ID for a match in the purchase record.
  - Have secondary ticket checks before people enter the stadium seats, to make sure guests have a ticket. 
  - Install security cameras at all the stadium entrances/exits and at the doors exiting the locker rooms (not inside the locker rooms), offices, and concessions.
  - Have concession cashier registers locked with a key or electronic password.
  - Have the scoreboard and sound system on a wired connection, which may take up physical space underground through the wiring but limits who can access the board and how.
  - Have locker rooms and offices locked with a key only admin have access too, not even the players, so the hours of access are limited to everyone. 
  - Have guards in the stands protecting from violence, and have bag checks at entry to check against weapons. 

## Problem 3
- Scenario: Surprise Birthday Party
- Assumptions:
  - There is a surprise party being planned for friend A by friend B, who is inviting a selective group of people.
  - The party is to be kept a secret from A, but not from the invitees.
  - The party is also to be kept a secret from non-invitees, because we don't want party crashers.
- Assets:
  - The confidentiality of the party: A must not know about the party until she walks into the event and is surprised. But the invitees must know about it so they can be there, and the non-invitees can't know about it so they are less likely to crash. 
  - The party food. B only bought enough food for the invitees + the birthday person A, so if anyone steals the food, there won't be enough. It must also be protected from damage (spilling stuff on it or being thrown away accidentally before the party).
  - Party decorations and party favors. These are essential to the party environment so they must be protected from tampering, destruction, or theft. 
  - Any personal valuables at the party such as people's coats, purses, etc.
  - The birthday gifts must be kept safe so the birthday girl can enjoy them after the party.
- Threats:
  - Theft of gifts, personal items, party favors, party decorations, or food.
  - Tampering with gifts, party favors, party decorations, or food.
  - People trying to get a fake invitation or find out the details of the party so they can crash (attend uninvited).
  - People telling the birthday girl A about the party.
  - People telling non-invitees about the party.
  - The invitees spilling the secret about the party beforehand.
- Countermeasures:
  - Exchange the invitation in person so B knows it has been delivered in one copy to the intended recipient.
  - Establish a dress code in person so that when someone shows up wearing something different you immediately know they shouldn't be at the party.
  - Exchange the invitations as close to the party date as possible (while still allowing sufficient planning time) so that people have less time to potentially spill the secret.
  - Have a person guarding the entrance only letting in the invitees and the birthday person A, and have the guard check ID's. 
  - Keep all personal items in a locked room like a coat closet when people come in, and give them a ticket voucher that contains a number corresponding to a number tagged on their item. This way, their items are in a secured room, and it is harder for people to pretend someone else's items are their when they steal them. Alternatively, you could tag the items with a photo of the person, possibly by taking a polaroid picture of them when they turn in the item and pinning it to the personal item. This way, the voucher being stolen wouldn't be an issue.
  - Lock up gifts in a private room, and take them elsewhere (possibly A's house) at some point mid-party so people who may have expected them to be in the party room who may want to steal them don't find them there. 

