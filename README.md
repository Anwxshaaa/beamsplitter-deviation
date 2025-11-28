# Michelson Interferometer Lab Set-Up

## Michelson Configuration based on parameters measured in the lab using FINESSE 3

In this project I tried plotting the interference pattern of the beam splitter used in the experiment using [`finesse`] (https://finesse.ifosim.org/docs/latest/examples/01_simple_cav.html) package

🎯 Aim: To analyse the deviation of real split ratios in the three 50:50 beam splitters from ideal condition

📋 Procedure:

- Using `finesse`, I configured the environment
- I created a basic Michelson model (laser → BS → two arms → mirrors; detector on the fourth port)
- The parameters considered are:
    - `l` →
