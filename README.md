# Personal-Assignment
#!/bin/bash
# Script to the get the sequence headers of file nrf1.fa and save into a file `sequence_names.txt` in the appropriate directory
# Usage: grep on file nrf1.fa
#QN1:Create a project directory called Exercise
mkdir Excercise

#QN2:create all the sub-directories needed
cd Excercise
mkdir python bash programming

#QN3:Download fasta file to the appropriate directory
cd bash
wget https://raw.githubusercontent.com/kipkurui/IntroductoryLinux/master/Data/nrf1_seq.fa

#QN4:Extract the sequence headers and save into a file sequence_names.txt
grep ">" nrf1_seq.fa > sequence_names.txt

#QN5:Save the commands you used in question 4 in a script file extract_seq.sh
#this script is what is required on question 4
