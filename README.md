BlackJack card game in SWI-Prolog
=========

## Introduction
Implementation of a *BlackJack* card game in `prolog` and `r..eal` library. The later is an interface to `R` statistical package within `SWI` code.  

To run the code one needs to have `R`, `R-dev`, `SWI-Prolog` and `r..eal` installed.  

## Pre-configuration
There are number of parameters available to customize the program:

## Executing the program(i.e. playing BlackJack)

To run the script:

     cd ~
     git clone git@github.com:So-Cool/BlackJack.git
     cd BlackJack
     swipl

and then within SWI-Prolog:

    consult('main').
    main.

After the game is finished there will be a *score graph* and *score table*(in the `.csv` format) produced within the `BlackJack` directory. The rows in the file are scores from particular round and the columns are in order: *dealer*, *AI1-deterministic table*, *AI2-deck probabilities*, *AI3-mixture of previous two*, *AI4-always hold* and finally, if enabled, **user's** score. The same order applies to vertical bars visible in the plot.  

---

**Warning!** it may become addictive **Warning!**  

---

**For more information please refer to the report available within this repository.**