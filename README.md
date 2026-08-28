# BMMB852_KL
# README.md
# README.md
# Week's Assignment

## 1 Create a directory and README.md file

### Commands

mkdir -p ~/assignment1
cd ~/assignment1
touch README.md

### What version is your samtools command in the bioinfo environment?

conda activate bioinfo

samtools --version

$ samtools --version
samtools 1.24
Using htslib 1.24
Copyright (C) 2026 Genome Research Ltd.

## Show commands needed to create a nested directory structure.

## Commands

mkdir -p data/raw results/scripts

## Show commands that create files in different directories

## commands
mkdir -p scripts

touch data/raw/input.txt
touch results/output.txt
touch scrips/analyze.sh

### create files with content

echo "input data" > data/raw/input.txt
echo "results" > results/output.txt
echo '#!bin/bash' > scripts/analyze.sh

### verify

find . -type f
   
## accessing these files using relative paths

cd ~/assignment1

### these are relative since they start from my current directory; assignment 1

cat data/raw/input.txt
cat results/output.txt
cat scripts/analyze.sh

###confirm where you are

pwd

###move between directories using relative paths (data for example)

cd data
cd raw
#### go back to README.md
cd ../..

##accessing files using absolute paths

### move up directories 

cd ../../../..

### absolute path

cat /Users/kenny/BMMB852/assignment1/README.md/data/raw/input.txt
cat /Users/kenny/BMMB852/assignment1/README.md/results/output.txt
cat /Users/kenny/BMMB852/assignment1/README.md/scripts/analyze.sh

### check location

pwd
