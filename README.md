# Goal-and-Environment-Framing-in-Optimal-Stopping-Problems
# These files correspond to the manuscript "The Effect of Goals and Environments on Human Performance in Optimal Stopping Problems" by Maime Guan and Michael D. Lee (2016).

# FramingOS_Supplementary.pdf is the supplementary information document for the paper. Contains details of the formal implementation of the graphical model in the paper, as well as three additional modeling analyses.

# SilvaData.mat contains the data for the paper. There are two data structures, d1 and d2, for the maximum-goal and minimum-goal conditions, respectively. Within d1 and d2, participants 1-28 are in the high-environment condition, and participants 29-56 are in the low-environment conditions. Each data structure contains the number of participants, the number of conditions, number of stimuli per problem, the condition assigned to each of the 56 participants, the stimuli each participant saw, the decisions made by each participant, the optimal decision for each participant's problems (as prescribed by the optimal stopping rule), the true maximum of each problem sequence for each participant, and the true minimum of each problem sequence for each participant.

# BF_max.txt is the graphical model for computing the Bayes factor comparing the thresholds of participants in maximum-high versus maximum-low conditions.

# BF_max_process.txt is the graphical model for the alternative process-oriented threshold choice model, computing the Bayes factor comparing the thresholds of participants in maximum-high versus maximum-low conditions.

# BF_max_sensitivitypreceding.txt is the graphical model for computing the Bayes factor for sensitivity or lack of sensitivity to the value of immediately preceding stimuli in a problem sequence, in maximum-high and maximum-low conditions.

# BF_min.txt is the graphical model for computing the Bayes factor comparing the thresholds of participants in minimum-high versus minimum-low conditions.

# BF_min_process.txt is the graphical model for the alternative process-oriented threshold choice model, computing the Bayes factor comparing the thresholds of participants in minimum-high versus minimum-low conditions.

# BF_min_sensitivitypreceding.txt is the graphical model for computing the Bayes factor for sensitivity or lack of sensitivity to the value of immediately preceding stimuli in a problem sequence, in minimum-high and minimum-low conditions.

# BF_congruent.txt is the graphical model for computing the Bayes factor comparing the thresholds of participants in maximum-high versus minimum-low conditions.

# BF_congruent_process.txt is the graphical model for the alternative process-oriented threshold choice model, computing the Bayes factor comparing the thresholds of participants in maximum-high versus minimum-low conditions.

# BF_incongruent.txt is the graphical model for computing the Bayes factor comparing the thresholds of participants in maximum-low versus minimum-high conditions.

# BF_incongruent_process.txt is the graphical model for the alternative process-oriented threshold choice model, computing the Bayes factor comparing the thresholds of participants in maximum-low versus minimum-high conditions.
