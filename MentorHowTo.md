# How to Mentor

## Summary
- groups of 5 students will work with a mentor to create an autonomous car
- A quick intro exercise will guide the steps to slowly add functionality
- Mob program w/ rotating driver (unless no one in the group can type on a keyboard)
- Focus on the students coming up with an experiment/expected outcome before trying to add new code
- Be flexible, happy and energetic. With younger groups things won't go smoothly so keeping positive energy going will be really helpful.
- Set really small goals (move the car, move the car further, turn the car, drive and turn, move the car to a target)

## Schedule
- 20 minutes
  - Settle in, find groups
  - Introduce group members to each other
  - Explain the exercise
- 1 hour
  - Do the xercise
  - Coding begins (5 minute rotations)
- 10 minutes
  - Regroup
  - Ending exercise
  
## Your role
- Enable the students in getting working code on the robot
  - Encourage quieter group members
  - Help them think of good experiments to try to get to the next step
- Handle running the car (git + ssh etc)
- Be familiar with the exercises and code
  
## How to introduce the group to each other
- Go around with names and something from a category (favorite tv show, favorite game, favorite color, etc.)
- Repeate and go around in the other direction (prompt for a different category)
- Set ground rules
  - 5 minute turns writing code
  - Typer must listen to group for input before writing code (they can contribute ideas when they aren't typing)
  - No code gets written until the WHOLE group understands the goal

## Exercise
- Robots have three core components: Sensing, thinking, and doing
- Form groups of 3 with each person taking on a task
- Navigate as a group "robot" following the rules described

## Coding
- Replace the "doer" role with the car + code to accomplish a simple task (like rolling the car and turning right)
- [Roughly follow this, but the age range seems too low to follow it explicitly](https://github.com/sturzl/mvavlabs/blob/master/labs/The%20Three%20Components%20of%20an%20Autonomous%20Robot.md)
- If somehow you end up with a group of experienced high schoolers, maybe follow that pretty closely
- [Here is the script you'll be working with](https://github.com/MVAV/car1/blob/master/car_script.py)

### API
- **rightWheel**(direction, seconds)  and **leftWheel**(direction, seconds)
  - Turns on the right wheel either forward or reverse, for a number of seconds
- **forward**(seconds) and **backward**(seconds)
  - Both wheels forward for a number of seconds
- Check out the script in the mentioned in the coding section

## How to use the car

(Sorry this should be better but its a work in progress)

Write some code then either:

- Commit to github
- Connect your laptop to the MVAV wifi
- SSH into the car
- Pull the code onto the car
- run the script
  
OR

  - connect to mvav wifi
  - ssh into the car
  - write code on the car or paste it in
  - run the script
