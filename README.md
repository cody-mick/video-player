# Code Foo 10 Frontend Engineer Application

---

## Introduction

Hello! My name is Cody Mickelsen and this is my application for the Frontend Engineer Internship. This project is something that I am proud of, as it was something that I had never done before and it pushed me to learn new things and grow as a developer.

I am from Rigby, Idaho, and am currently a student at Brigham Young University - Idaho. I have been studying software engineering, and recently added a Web Development emphasis on to that in the past year or two once I realized that I really had a passion for making all things web. I have taken several classes on Frontend Development, and am starting some classes on backend development. I hope one day to be involved on Full Stack projects, but I do want to start on some Frontend developer opportunities. I currently still live in Rigby, along with my wife and two puppies. We live it up all the time! I am a person that likes to have fun, but also someone that likes to watch and listen when something is being taught to me. My learning style is definitely one of read, watch, perform. Sometimes I will admit though that that has gotten me stuck in an endless tutorial loop, but I have been working on just jumping in to projects in order to have more "trial by fire" experiences that will help me learn more effectively.

I would say that I have a pretty strong connection to IGN, I've been playing video games as long as I can remember, and referencing IGN guides for almost as long as that. My most prominent memories are of looking up ways to beat the Pokemon games, more specifically Pokemon Diamond. Finding locations of different Pokemon, answers to puzzles that I was stuck on, and anything inbetween! I also trust the reviews that IGN puts out, and rank it as one of my foremost sources of authority on how good a game is. If I am looking to purchase a game, chances are that I have watched the review for said game and take that heavily into account. So I would love the opportunity to learn from you guys, and to experience what the real development world is like, and even more so that this revolves around my favorite industry.

## Professor Laventon's Request

So, in order to solve this problem, I broke it down into some smaller chunks and began to answer my small questions while I pieced together the big picture. Those small questions were as follows:

1. How many residences are in Jubilife Village?
2. How much power will those residences be using?
3. How much power does the HQ, Training Grounds, and Farm consume?
4. How much power can a Voltorb produce?

I did some research and found that Jubilife Village has 21 "standard households". These are residential dwellings, included in this are the shops and the Galaxy Team Quarters. This only leaves the Galaxy Team HQ, Training Grounds, and the Farm. After doing a bit of digging, I found that the average american household consumes about 30kWh (kilowatt-hours) of power a day. Then I took some liberties based on size and function and assumed the HQ would consume 3x that amount to use 90kWh/day, this due to its size and the presence of not only the Pokemon Lab, but Cylene and Commander Kamado's offices. The Training Grounds, I estimate, will consume about 60kWh per day, for the presence of pokemon battles and other training opportunities, and the farm would consume only 45kWh per day since the irrigation and field creation is performed by Pokemon, and the power would be used mainly for tools for the farmers. This brings our grand total up to 825kWh/day. BUT WAIT! Jubilife Village was around 100 years ago, and couldn't possibly need as much power as that, since my statistics are from the average American home in 2020. So I reduced that number down by 225kWh, and we are left needing 600kWh/day. That is our magic number. If we want to find out how many watts per day that is, we can use this formula: watts = (kWh X 1,000) / hrs. If we plug in our numbers, we get something that looks like this: watts = (600 X 1,000) / 24. Which boils down to 600,000 / 24. This equals 25,000, which means that we need 25,000 watts/day to power Jubilife Village.

So now that we have calculated the power needs of Jubilife Village, we need to find out the electric potential of our lovely little Voltorbs. I started by using the equation for power, which is Power(Watts) = Volts x Amps. This was nice to look at, but eventually didn't end up getting used. When I did some more research on our little friends, I found that each move it can learn has a stat called _power_. Which means that we don't neccessarily have to calculate how much a Voltorb can produce, that power varies from move to move.

For my answer I chose to use the move Thunder. This move has a power stat of 100. This means that thunder outputs 100 watts of power each time it is used. Now that we know the electric potential of our Voltorbs, we can match this against our power need of 25,000 watts/day. At this point in time we could report to Laventon and let him know that we are going to need 250 Voltorbs to be able to generate the needed power. That's quite the claim. And a mountainous task to catch that many. But then I remembered that a single Voltorb can use Thunder _5 times_ before needing to recharge. This boosts our power output to 500 watts per Voltorb, and when we check this amount against our needed power of 25,000 watts/day, we get down to the real answer. **We will only need 50 Voltorbs to power all of Jubilife Village.**

Which should be no problem if we are shiny hunting a massive mass outbreak!

## Frontend Project

### Responsive Video Player using React
