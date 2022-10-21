# HAQS-QUSTEAM-2022
The HAQS QuSTEAM challenge

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/qBraid/HAQS-QUSTEAM-2022.git)

Repository containing challenges for the qBraid HAQS 2022 quantum computing hackathon.

For non-registered individuals:
https://qbraid.com/haqs

For participants:
https://account.qbraid.com/haqs



To submit your hack, create a pull request from your team's named branch (created during Step 3 above) following challenge submission instructions.

For help with these instructions, follow along with the HAQS getting started video demo: https://youtu.be/uYGV9w2DUcg

## About QuSTEAM

QuSTEAM is a nonprofit organizaton of colleges, universities, and employers supporting expansion of quantum information science and engineering undergraduate education to diverse campuses to achieve a diverse workforce. Fall 2022, we are piloting the first four courses of a quantum information minor. Created by 75 professors from Ohio State and two dozen other institutions (a dozen HBCUs, six R1 research universities, small colleges, community colleges, ...) we aim to support adoption of QISE coursework at 300 campuses by 2027.

## The QuSTEAM Hackathon Challenge

Investigate entanglement and noise. Explain your experiment and result and a level accessible to relative beginners.

### Getting started

1. Fork this repository into your account, and copy its git clone url e.g. `https://github.com/<user>/HAQS-QUSTEAM-2022.git`
2. At the top of this `README` in the forked repo, click the **Launch on qBraid** button to clone this repository and launch qBraid Lab.
3. Open terminal (first icon in the **Other** column in Launcher) and `cd` into the HAQS repo. Set the repo's remote origin using the git clone url you copied in Step 1, and then create a new branch for your team:
```bash
cd HAQS-QUSTEAM-2022
git remote set-url origin <url>
git branch <team_name>
git checkout <team_name>
```

## Minimal elements for an entry in the QuSTEAM Challenge

1.  Jupyter notebook with code and explanation
       
2.  A video of 3-5 minutes, embedded in or linked from the Jupyter notebook. The video should summarize your experiment and results. A text file containing a transcription of the audio.
        
3. The Jupyter notebook should include results and analysis for an experiment in which:
        
   a. Prepare a state in which two or more qubits are entangled.
 
   b. Two or more distinct conditions are used during a delay between the preparation of the entangled state and the measurement of the extent of entanglement. Examples:
   
      * Prepare a Bell state and wait a varying amount of time to measure decoherence vs. time.
      * Prepare a Bell state and, during a set amount of wait time, apply single qubit gates to an adjacent qubit.
      * Prepare a Bell state on various distinct pairs of qubits on a particular platform. 
                  
   c. A measurement of entanglement is made. Note that how to measure entanglement among three or more qubits is an ongoing area of study, and any method may be used with explanation. 
        
# The Jupyter notebook - both code and writing - should:

**Do it for the audience.** Include written explanation in English and mathematics that a first-year college student who is marginally prepared to take calculus will understand your claims, descriptions, and reasoning. Specifics on this requirement are reflected in the rubric, which is below (coming).

**Do it for free.** Include code that will execute on a simulator backend.

**Do it for real.** Include code that will execute on one or more physical backends.

# Background knowledge

You may assume exposure (requiring a reminder) to specific entry-level QISE knowledge:

 * The state of a qubit can be expressed as a|0> + b|1>. 
 * After measurement, a qubit is in a state in that basis corresponding to the measured outcome.
 * Two-slit experiment, repeated Stern Gerlach measurements (not mathy), delayed choice experiments.
 * Representing a single qubit state on the Bloch sphere.
 * Representing a qubit using a linear combination of kets in the z basis: |010> (or |0>|1>|0>) or |2>. 
 * Construction of a quantum circuit using a Python library.

Do not assume exposure or knowledge of:

* mathematically how to change bases (arbitrary angles)
* the tensor product.
* the density matrix

You may assume (without a reminder)
 
 * expression of a complex numbers as $re^{i\theta}$, a + bi, or a point in the complex plane
 * multiplication (scalar and vector product) and addition of real vectors 
 * right triangle and unit circle trigonometry

# Rubric

Entries will be evaluated by a panel based upon:
 
  * Explanation of experimental design
  * Explanation of entanglement accessible to the beginner
  * Explanation of the meaning and signficance of the results 

