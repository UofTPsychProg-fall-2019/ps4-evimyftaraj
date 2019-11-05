# pseu-pseu-pseudo

## Give us your pseudocode!
For this problem set, your task is to write out the pseudocode for the experiment you'll be implementing for assignment #1. Think about the logic of your experiment, if/how you want to counterbalance, the sequence of a trial, what measures you want to collect, and so on. Then, using pseudocode that makes sense to you, write it out in some sort of structured format (e.g., detailed paragraphs, bulleted sequence of operations, indented code-like commands). Just make sure it is both human readable and detailed. If you don't know all the details of your experiment, that is fine. Make something up that's sensible, but the closer you are to the experiment you will implement, the more helpful this assignment will be later on!

## Deliverables
Your submission should be 1 text file with:
1. A brief paragraph describing of your experiment
2. Pseudocode detailing the hierarchy of your experiment

1. The experiment I will conduct is related to the concept of the Òbutcher on the busÓ phenomenon, which is a measure of memory for peopleÕs faces when these faces are viewed in a context that is different from the faceÕs learnt context (i.e., we see a person on the bus, and we feel as if we have seen this person before, and evidently, after deliberate thought, we can recollect that this person is an employee of a grocery store we visit frequently). I am testing peopleÕs memory for faces Ð specifically, their recollection process (i.e., we can remember that a person we see on the bus is the person that works in our favourite grocery store) and their familiarity process (i.e., we feel as if we know a person, but cannot remember from where we know this person). The participants of this experiment will be healthy adults (young and old), but also older individuals with amnestic mild cognitive impairment (aMCI). These individuals with aMCI should have impaired recollection, but also impaired familiarity compared to healthy adults. This experiment will be conducted using E-prime. 

The experiment itself will involve presenting participants with 72 face-context paired images over 180 trials (this means that half of the images will be shown on more than one trial Ñ specifically, 36 of the images will be shown four times, and the other 36 images will be shown only once). Each image will be presented on the screen for 3 seconds. In the test phase, there will be 144 face-context images presented across four conditions: (a) 36 studied faces shown with the same context as in the study phase, (b) 36 studied faces shown with a new context that has not been studied, (c) 36 new faces shown with a studied but not exact context (e.g., a new library) and (d) 36 new faces shown with a new context that has not been studied. Participants will rate each face presented on a scale of 1 (definitely-old) to 6 (definitely-new) by using the keyboard. If participants select one of the three ÔstudiedÕ options (definitely-old, fairly sure-old, guess-old), they will then indicate if their decision was based on familiarity or recollection, by clicking keys corresponding to ÔfamiliarÕ or ÔrememberÕ, respectively.

2. > Subject = input() 
> If subject is odd, then counterbalance response keys = 1 to 6 
	Else, counterbalance response keys = 6 to 1 
> Read stimulus (72 images) Ð 36 of these stimuli will be presented 4 times, and 36 of these stimuli will only be presented once
> Shuffle stimuli order
> Present each stimulus for 3000 ms 
> After 180 trials, present statement on the screen saying ÒYou are 	free to take a break if you wish. Continue when you are readyÓ
> Now the test phase begins:
> Instructions for the test phase will be announced to participantÉ
> Read stimulus on screen
> Response = keyboard behaviour 
> Shuffle stimuli: 144 total (36 stimuli will be from the study 	phase, 108 stimuli will be completely new)
> Check that four stimuli from the same condition are not shown sequentially (if they are, shuffle stimuli again Ð do this to avoid priming effects)
> From the 144 stimuli total in the test phase, 72 stimuli will be faces presented in study phase (36 of those faces will be exactly the same with identical context, while 36 of those faces will be studied faces but with a new context) 
> Half these studied faces (regardless of old or new context) are from repetition group 4, and the other half of studied faces are from repetition group 1
> Each stimuli presented for 3000 ms
> After each stimulus time is completed, show a blank screen
> Only allow responses after image presented for 3000 ms and the screen is blank
> Let participants have unlimited time to press on keyboard keys (from 1 to 6, or 6 to 1) regarding how confident they are in having seen the face in the stimuli before
> If participant selects 1, 2, 3 in counterbalancing order 1 
	Or participant selects 3, 4, 5 in counterbalancing order 2
 	Then participant has to choose between remembering or feeling the image is familiar (R or K on keyboard) + track response
 	Else track response + move on to next stimuli
	Save responses with subject number, counterbalancing order, reaction time) 
> After all stimuli presented, present a blank screen with a thank you note. 

  


