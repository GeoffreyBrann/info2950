# info2950
Info 2950 semester long project

Geoff:
2019 FanGraphs UBR Stats.csv, FanGraphs WRC+ Data.csv
Team,PA,BB%,K%,BB/K,AVG,OBP,SLG,OPS,ISO,Spd,BABIP,UBR,wGDP,wSB,wRC,wRAA,wOBA,wRC+
Need individual UBR stats from this file, looks very similar to the FanGraphs WRC+ Data.csv. We want both wRC+ and UBR from these two. I don't know what BsR is on the FanGraphs WRC+ Data.csv, maybe another baserunning stat?

2019_batter_OPS+.csv
Rk,Name,Age,OPS+,Pos Summary
This file contains name, and OPS+, which means we can tack on the OPS+ column onto any other dataframe with names as long as they match up. Only need OPS+ from this file.

statcast_stats_2019.csv
last_name, first_name,year,xba,xslg,xwoba,xobp,xiso,exit_velocity_avg,launch_angle_avg,sweet_spot_percent,barrels,barrel_batted_rate,solidcontact_percent,flareburner_percent,poorlyunder_percent,poorlytopped_percent,poorlyweak_percent,hard_hit_percent,z_swing_percent,z_swing_miss_percent,oz_swing_percent,oz_swing_miss_percent,oz_contact_percent,out_zone_swing_miss,out_zone_swing,out_zone_percent,out_zone,meatball_swing_percent,meatball_percent,pitch_count_offspeed,pitch_count_fastball,pitch_count_breaking,pitch_count,iz_contact_percent,in_zone_swing_miss,in_zone_swing,in_zone_percent,in_zone,edge_percent,edge,whiff_percent,swing_percent,pull_percent,straightaway_percent,opposite_percent,batted_ball,f_strike_percent,groundballs_percent,groundballs,flyballs_percent,flyballs,linedrives_percent,linedrives,popups_percent,popups,n_bolts,hp_to_1b,sprint_speed,

This file contains the majority of our data, including name, and a lot of statcast stats. I think we should use this as our main dataframe, then add other data onto this that is does not already contain (like wOBA, UBR, OPS+, wRC+)

<<<<<<< Updated upstream
Data Cleaning: Jonas
Monday-----> Have UBR and wRC+ stats of individual players for 2019 season
and ensure all data has significant values(No NaN entries etc.)
Thursday---> Have each of the csv Dataframes narrowed to the column that pertains to the specific stat and append the columns to the statcast dataframe
=======
Geoff:
Data description. Have an initial draft of your data description section. Your data description should be about your analysis-ready data.

    A general description of the data, including where we got it from, the form that it takes.
    A key that describes each individual column of data that we have so it can be read easily.

Data limitations. Identify any potential problems with your dataset.

    We will find limitations as we go, but right now our dataset seems pretty comprehensive.

Questions for reviewers. List specific questions for your peer reviewers and project mentor to answer in giving you feedback on this phase.

    Everyone should at any point write down questions they have (in this section designated Questions in the readme), I will compile them for the reviewers, as well as any other questions I can think of.

Questions:

I will have the Data description done by Wednesday morning Oct. 7, and I will work on questions and limitations as we find them.
>>>>>>> Stashed changes
