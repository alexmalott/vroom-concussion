# Virtual Concussion Assessment Tool
The vCAT is a VR experience designed to provide an objective measurement of the degree of impairment of previously concussed (or otherwise impaired) people.
It was built in 48 hours during the 2018 CSU VR/AR Create-A-Thon with Unreal Engine 4.20 blueprints and took first place overall.

## Assessments
The tool is currently comprised of four separate tests designed to deliver a rating of zero to five points (five indicating no impairment) to indicate the level of impairment in various areas of cognition.

### Reaction
The reaction assessment tests the hand-eye coordination and reflex of the participant by simulating a ping-pong game.  Scoring is based on the amount of time taken to return a serve (or otherwise contact the ball) compared to the theoretical minimum time.

### Balance
The balance test asks the participant to balance on one foot with their arms outstreched, and notes any deviation from the position with an allowed hand movement of about 20cm.  Scoring is accomplished by dividing the movements observed by the maximum number of movements that could be recorded. 

### Memory
The memory test shows the participant a grid of cubes where some are highlighted - then disables this highlighting, performs some rotations to the grid, and asks the participant to select the cubes that were previously highlighted.  Scoring is based on the number of cubes that were selected correctly and those that were not.

### Focus
The focus test asks the participant to simultaneously monitor visual and auditory stimuli - indicating when a specific condition occurs.  The test periodically generates this, and other, conditions.  The scoring is based on the number of stimuli correctly identified, and the number of false positives or true positives ignored.
