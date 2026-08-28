# BMMB852_KL
# README.md
# README.md
# Week's Assignment

## 1 Create a directory and README.md file

### Commands

```bash
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
