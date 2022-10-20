# HAQS-QUSTEAM-2022
The HAQS QuSTEAM challenge

## About QuSTEAM

QuSTEAM is a nonprofit organizaton of colleges, universities, and employers supporting expansion of quantum information science and engineering undergraduate education to diverse campuses to achieve a diverse workforce. Fall 2022, we are piloting the first four courses of a quantum information minor. Created by 75 professors from Ohio State and two dozen other institutions (a dozen HBCUs, six R1 research universities, small colleges, community colleges, ...) we aim to support adoption of QISE coursework at 300 campuses by 2027.

## The QuSTEAM Hackathon Challenge

Produce teaching resources to support a student who wants to be able to explain and investigate entanglement.

## Minimal elements for an entry in the QuSTEAM Challenge

1.  Jupyter notebook with code and explanation
       
2.  Two videos of 1-3 minutes each, embedded in or linked from the Jupyter notebook. One video should summarize your experiment and results. Both videos should be accompanied by a text file containing a transcription of the audio.
        
3.  One multiple choice question for each video to check for understanding.  comprehension question per video. 
        
4. Data shown in the Jupyter notebook should include results and analysis for an experiment in which:
        
 a. Qubits are entangled
 
 b. One of two or more different protocols (e.g. wait 100 ms, wait 1 s) are followed to allow a potentially distinct extent or type of undesired decoherence to occur
                  
c. A measurement of entanglement is made. Note that how to measure entanglement is an open question, and any method may be used with explanation. 
        
# The Jupyter notebook - both code and writing - should:

**Do it for the audience.** Include written explanation in English and mathematics that a first-year college student who is marginally prepared to take calculus will understand your claims, descriptions, and reasoning. Specifics on this requirement are reflected in the rubric, which is below (coming).

**Do it for free.** Include code that will execute on a simulator backend.

**Do it for real.** Include code that will execute on one or more physical backends.

# Background knowledge

You may assume exposure (requiring a reminder) to specific entry-level QISE knowledge:

 * The state of a qubit can be expressed as a|0> + b|1> 
 * After measurement, a qubit is in a state in that basis corresponding to the measured outcome.
 * Two-slit experiment, repeated Stern Gerlach measurements (not mathy), delayed choice experiments
 * Representing a single qubit state on the Bloch sphere
 * Representing a qubit using a linear combination of kets in the z basis: |010> (or |0>|1>|0>) or |2>. 

Do not assume exposure or knowledge of:

* mathematically how to change bases (arbitrary angles)
* a measurement operator
* the tensor product.
* the density matrix

You may assume (without a reminder)
 
 * expression a complex numbers as $$re^{i\theta}$$, a+bi, or a point in the complex plane
 * multiplication (scalar and vector product) and addition of real vectors 
 * Right triangle and unit circle trigonometry

Rubric:

Points for explicating at a accessible level for the stated audience:

 * Teleportation
 * Bell's Inequality
 * CHSH
 * CHSH Game
