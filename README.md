# MSK_Combined

An attentional blink paradigm which 'combines' McLaughlin, Shore, & Klein (2001; T1 difficulty mixed within trials) and Shore, McLaughlin, & Klein (2001; T1 difficulty is blocked across trials). 

In the present case, T1 difficulty is blocked for 3 blocks, and mixed for the remaining three blocks. Which is experienced first (blocked or mixed) is randomized across participants.

Designed to be component of a 3-part study, the other two components being direction replications of the aforementioned papers.

Note: Within each experiment, participants complete a practice block of 30 trials wherein T1 difficulty is varied across trials.

In order to run this experiment, you first need to install KLibs, the framework through which this project was developed. To do that go here: https://github.com/a-hurst/klibs and follow the steps listed. That page will also list the steps needed to execute the experiment.

Note: Currently all three projects are setup under the assumption that multiple subjects will be concurrently tested. If you are only intending to run one subject at a time, it is recommend to switch 'multi_user_mode' (line 10 in 'params.py', found in ExpAssets/Config) from True to False.

Note: Experiment code assumes that your display refreshes at the 'standard' rate of 60Hz. If this isn't the case for you, stimulus durations will need to be adjusted to match, feel free to email Brett for clarification on this if needed.

(Sample GIF of trial sequence soon to follow)
