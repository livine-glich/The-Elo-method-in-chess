# The Elo Method in Chess

This repository contains the data analysis and challenge solutions exploring the **Elo rating system** applied to chess match data. 

The primary objective of this project is to contrast the traditional cumulative scoring system (Point Ratings) against the dynamic Elo framework, specifically evaluating how match volume impacts overall player rankings.

## Repository Contents

Elo method in chess.Rmd: The source R Markdown file containing all optimized R code blocks, mathematical proofs, and comprehensive analytical findings.
Elo-method-in-chess.html: The final compiled HTML report complete with fully rendered markdown narrative and data visualizations.

## Core Analytical Insights

1. White's Initiative Advantage: The dataset reinforces the classical chess theory that moving first offers a clear competitive edge (White Win Rate: 32.5% vs. Black Win Rate: 23.4%).
2. Zero-Sum Mechanics: Includes a formal step-by-step mathematical proof and subsequent floating-point computer validation verifying that the sum of all net ratings within the system constantly balances out to precisely zero.
3. Volume vs. Performance Quality: Point ratings exhibit a near-perfect correlation (0.99) with active match volume. Conversely, the Elo metric corrects for this bias by evaluating individual performance relative to opponent strength rather than gross participation.
