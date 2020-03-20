# Udacity driving simulator executable on Mac OS Catalina!

Currently the Udacity driving simulator used for the Self Driving Car Nanodegree cannot be run on the Mac OS Catalina. So I've compiled the binary myself using [Udacity's driving simulator] (https://github.com/udacity/self-driving-car-sim) myself (tested on Mac Catalina OS 10.15.3)


# Instructions to unzip the split zip files

These zip files have been zip and splitted using the `zip` command in Mac OS Terminal, to unzip it you *must* unzip it using the Terminal too.

Here are the bash commands to unzip it correctly.

```console
cat use_terminal_unzip_only_term1_*.* > term1_sim_mac.zip
unzip term1_sim_mac.zip

cat use_terminal_unzip_only_term2_*.* > term2_sim_mac.zip
unzip term2_sim_mac.zip

cat use_terminal_unzip_only_term3_*.* > term3_sim_mac.zip
unzip term3_sim_mac.zip
```