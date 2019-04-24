# How to Mentor

## Summary
- groups of 5 students will work with a mentor to create an autonomous car
- A quick intro exercise will guide the steps to slowly add functionality
- Mob program w/ rotating driver (unless no one in the group can code)
- Focus on the students coming up with an experiment/expected outcome before trying to add new code

## Schedule
- 20 minutes
  - Settle in, find groups
  - Introduce groups to each other
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
- Handle running the car (git + ssh etc?)
  
## How to introduce the group to each other
- Go around with names and something from a category (favorite tv show, favorite game, favorite color, etc.)
- Repeate and go around in the other direction (prompt for a different category)
- Set ground rules (5 minute turns writing code, MUST listen to group for input before writing code, no code gets written until the WHOLE group understands what the goal is)

## Exercise
- Robots have three core components: Sensing, thinking, and doing
- Form groups of 3 with each person taking on a task
- Navigate as a group "robot" following the rules described

## Coding
- Replace the "doer" role with the car + code to accomplish a simple task
- Replace the thinker role and accomplish a more complex task
- If somehow you end up with a group of experienced high schoolers, maybe replace the sensor role with the camera
- API is as follows:
  - rightWheel(direction, seconds)  and leftWheel(direction, seconds)
    - Turns on the right wheel either forward or reverse, for a number of seconds
  - forward(seconds) and backward(seconds)
    - Both wheels forward for a number of seconds

## How to use the car

(Sorry this should be better but its a work in progress)

- Write some code then either:
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
