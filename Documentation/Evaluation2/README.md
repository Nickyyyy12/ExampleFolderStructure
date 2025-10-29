1. Introduction and Background
   
This is my report for the second prototype (P2). After I showed my first prototype (P1),
people thought the idea of separating MR and VR was cool, and they understood who
the "host" and "guest" were. But the biggest problems were that the space felt empty
with nothing to do, and some people said it might feel weird for the MR and VR people
to talk to each other.

So for P2, my main goal was to fix the "nothing to do" problem. I wanted to add a feature
everyone could use, like a whiteboard. I also wanted people to be able to see each other
instead of just floating VR controllers, so I added avatars.
What I Did in P2

To make this happen, I spent a lot of time learning Unity's networking tools (Netcode for
GameObjects, Lobby, Relay) and the Meta Avatars SDK. This was all brand new to me.
Here are the features I managed to build:

3. What I Did in P2
   
2.1 I Added a Shared Whiteboard

Why: Because everyone from the last feedback session said this was the kind of tool
that was missing most.

How: I put a whiteboard in the scene and wrote code so players could draw on it
with their controllers. The hardest part was making the drawings show up for everyone
else. I used network variable synchronization from Netcode and it took me a few days to
figure out, but it works now.

2.2 I Added Meta Avatars

Why: I thought that if people could see each other's avatars, it would feel better to
talk, even with the different MR and VR views.

How: Integrating the Meta Avatars SDK was more complicated than I expected. I had
to link it with the Unity Lobby service to load each person's avatar when they joined a
room. Now, when people get into the same room, they can see each other's avatars, and
their head and hand movements are synced.

5. What Happened on Demo Day

During this demonstration, I did not manage to get any substantive feedback regarding
the new features of the project. The instructor's feedback focused primarily on the
technical failure itself, suggesting that it was caused by my inadequate preparation. In
reality, I had run a full and successful test of the project the day before, so this comment
was quite difficult for me to hear. Under the time pressure and stressful atmosphere of
the situation, the entire exchange revolved around "why it failed" rather than providing
an opportunity to discuss the project's design and new features. This was very frustrating,
as I was eager to receive feedback on my creative ideas, not a judgment on an
unexpected technical accident

My Reflections

About the Failed Demo

My Tech Prep Wasn't Enough: The first thing I learned is that just because it works at
home, doesn't mean it will work anywhere else. The classroom's Wi-Fi, other people's
hardware... anything can go wrong. I was too naive.
I Need a Backup Plan: This was the biggest lesson. I kept thinking, "if only I had recorded
a video beforehand." If the live demo failed, I could have at least played the video to show
the instructor what I actually built. I will definitely do that next time.
Too Much Pressure, I Panicked: When I realized it wasn't connecting, my mind went blank.
With so little time left, I couldn't even speak clearly. I admit I did not handle the
unexpected situation well.

4.2 My Thoughts on the Project Itself

From a coding perspective, I think I achieved my goals for P2. I successfully built the
whiteboard and avatar features.

But from a presentation and evaluation perspective, I failed. If nobody sees what you
made, it's like you didn't make it. The project is stuck now because I don't know what
people think of my new features.

What I Plan to Do Next
   
5.1 First, I Have to Show the Instructor What I Actually Made
My top priority is to communicate with the instructor and see if I can get a few more
minutes to show them the working version. I can't move forward without feedback.
5.2 Fix the Awkward Communication Problem from Last Time

After I get feedback on the whiteboard and avatars, I need to start thinking about
how to solve the "awkward communication" problem between MR and VR from P1.

5.3 Make the Project More Stable and Create a Backup Video

I will spend time optimizing the connection process to make it less prone to errors.
And, before the next evaluation, I will definitely record a high-quality demo video, just in
case.
