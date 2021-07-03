# MLB Spin Rate Analysis

## Goal
Compare pitcher's spin rates before and after June 3, when umpires started checking pitchers randomly throughout the game for the illegal sticky stuff pitchers use to increase spin rate and movement in their pitches.

## Approach
Probably a simple t-test. Also, spin rate is one variable. Spin-to-velocity ratio (SVR) is another

## Look at
Gerritt Cole, Trevor Bauer, Ryan Pressley, Tyler Glasnow

In previous years is there any significant drop in SVR in the second half of the season?

Is there a significant drop overall among all pitchers?

Is the drop by Cole, Bauer, et al, more than the drop from all pitchers?

Is there any advantage to using non-parametric tests? Check for normality of data.

## pybaseball
Use the pybaseball package to access statcast data

FT (two-seam fastball), FF (four-seam fastball), CU (curveball), and FC (cutter) are the relevant pitches


