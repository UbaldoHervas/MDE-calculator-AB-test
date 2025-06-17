# MDE-calculator-AB-test
MDE calculator for AB testing projects to calculate your sample size properly.
This calculator is useful to determine the amount of minimum detectable effect you can achieve based on:

- Alpha
- Beta
- Your population
- Your (primary AB testing metric) conversion rate

How? Based on the population, you can calculate your MDE properly. I used a z-test approach to calculate this. But I think it works nicely in other statistical test methods.

Warnings:

- The more traffic your test gets, the less MDE you need. I recreated a visualization to show how it works (10 weeks maximum).
- The calculator assumes linearity (CR and traffic). Maybe I will modify this assumption in the future. Take this into account if you calculate MDE during n weeks.
- Z-test is used to calculate this. Be aware of using different statistical test methods could need different approaches.
