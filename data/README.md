# ABOUT

This folder contains data generated during this research project. The following files with there column names have been described.

* main.csv - a summary of the relationship between exfagellation, gametocytemia, and infection for all experiments; column names:
    * "feed date" - date culture was fed in SMFA
    * "seed date" - date culture was seeded
    * "strain / code" - the parasite strain of the culture and its code (optional)
    * "feed" - feed number 
    * "exflagellation (%)" - percent exflagellation, percentage of cells in culture exflagellating
    * "gametocytemia (%)" - percentage of cells in culture that are stage V gametocytes
    * "hematocrit (%)" - percentage of blood volume that is red blood cell
    * "culture age" - time (days) between seed date and the feed date
    * "dilution gametocytaemia (%)" - gametocytemia that the culture was diluted down to before feeding during SMFA
    * "oocysts, avg. per mq" - average of oocysts produced by mosquitoes for the given feed and strain
    * "infectivity (%)" - percentage of mosquitoes with at least one oocyst for the given feed and strain
    
* oocysts.csv - a summary of infection results across feeds 13 to 20; column names:
    * "dissection date" - date mosquitoes from the given pot were dissected
    * "infection age" - time (days) between SMFA feed date and dissection date
    * "mated" - the row describes mated or virgin mosquitoes (T/F)
    * "oocyst total" - total number of oocysts yielded by the pot
    * "midguts total" - total number of midguts dissected
    * "oocysts, avg. per mq" - equal to, oocyst total / midguts total
    * "oocysts, median - middle oocyst set of the given pot
    * "oocysts, std. dev. - oocyst yield standard deviation of the given pot
    
    * "*feed date*"
    * "*strain / code*"
    * "*feed*"
    * "*infectivity (%)*"
    * "*gametocytemia (%)*"
    * "*exflagellation (%)*"

* raw_exflagellation.csv - raw data gathered when measuring exflagellation; column names:
    * "exflagellation, per mL" - estimated exflagellation events per mL of sample
    * "RBC, per mL" - estimated red blood cells per mL of sample
    * "exflagellation, top-left" - exflagellation events in top-left region
    * "exflagellation, top-right" - exflagellation events in top-right region
    * "exflagellation, bottom-right" - exflagellation events in bottom-right region
    * "exflagellation, bottom-left" - exflagellation events in bottom-left region
    * "RBC, top-left" - red blood cells in top-left region of center grid
    * "RBC, top-right" - red blood cells in top-right region of center grid
    * "RBC, bottom-right" - red blood cells in bottom-right region of center grid
    * "RBC, bottom-left" - red blood cells in bottom-left region of center grid
    * "start (MM:SS:mm)" - start time for counting exflagellation (minutes, seconds, millsec)
    * "end (MM:SS:mm)" - end time for counting exflagellation (minutes, seconds, millsec)
    * "Notes" - notes or observations taken during measurement
    
    * "*feed date*"
    * "*strain / code*"
    * "*exflagellation (%)*"
    
    
* raw_gametocytemia.csv - raw data gathered when measuring gametocytemia; column names:
    * "date" - date that the measurement was taken
    * "replicate" - was this row a replicate (T/F)
    * "RBC total" - the total number of red blood cells counted ~350
    * "gametocyte total" - the total number of stage V gametocytes counted
    * "males" - the number of male gametocytes in the sample
    * "females" - the number of female gametocytes in the sample
    * "sex ratio (M/F)" - equal to, males / females
    
    * "*strain / code*"
    * "*feed*"
    * "*culture age*"
    * "*gametocytemia (%)*"
    
    