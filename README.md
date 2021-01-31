# NU_MS_EDA_Project

## Data:
1. COVID Data retrieved on 1/31/2021 from: https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-in-the-United-St/kn79-hsxy/data
2. Massachusetts crime data from: https://masscrime.chs.state.ma.us/public/View/dispview.aspx


## Git commands:
__To Clone:__

Run:
`git clone https://github.com/robords/NU_MS_EDA_Project.git`

For example:
```
(base) C:\Users\Curt-RBS\Desktop\NU>git clone https://github.com/robords/NU_MS_EDA_Project.git
Cloning into 'NU_MS_EDA_Project'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), 4.08 KiB | 2.04 MiB/s, done.

(base) C:\Users\Curt-RBS\Desktop\NU>dir
 Volume in drive C is Blade Stealth
 Volume Serial Number is E07F-41E3

 Directory of C:\Users\Curt-RBS\Desktop\NU

01/29/2021  08:25 PM    <DIR>          .
01/29/2021  08:25 PM    <DIR>          ..
01/10/2021  01:36 PM    <DIR>          .ipynb_checkpoints
03/08/2020  10:46 AM    <DIR>          Math400
11/14/2020  11:50 AM    <DIR>          MSDS401
01/11/2021  08:22 PM    <DIR>          MSDS430
01/28/2021  09:19 PM    <DIR>          MSDS430Robords
01/29/2021  08:25 PM    <DIR>          NU_MS_EDA_Project
               0 File(s)              0 bytes
               8 Dir(s)  58,622,615,552 bytes free
```

__To Pull:__
* Note: make sure you're in the directory `NU_MS_EDA_Project`
If you're using the terminal, to pull the latest, run:
`git pull`

For example:
```
(base) C:\Users\Curt-RBS\Desktop\NU\MSDS430Robords>git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 6.37 KiB | 296.00 KiB/s, done.
From github.com:robords/MSDS430Robords
   cf7bfd2..ca3b840  main       -> origin/main
Updating cf7bfd2..ca3b840
Fast-forward
 Module_3_Python_Assignment - Robords.ipynb | 359 +++++++++++++++++++++++++++++
 1 file changed, 359 insertions(+)
 create mode 100644 Module_3_Python_Assignment - Robords.ipynb
 ```


__To Push:__
* Note:  make sure you're in the directory `NU_MS_EDA_Project`
More info here: https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository
1. Start tracking the new file, or the file you've changed by running:

`git add <filename>`

You can do this for multiple files:

`git add <filename> <filename>`

Or all files:

`git add *`

2. Commit the changes:

`git commit -m "<description of the changes>"

3. Push the changes:

`git push`

For example:
```
(base) C:\Users\Curt-RBS\Desktop\NU\NU_MS_EDA_Project>git add  Provisional_COVID-19_Death_Counts_in_the_United_States_by_County.csv
warning: LF will be replaced by CRLF in Provisional_COVID-19_Death_Counts_in_the_United_States_by_County.csv.
The file will have its original line endings in your working directory

(base) C:\Users\Curt-RBS\Desktop\NU\NU_MS_EDA_Project>git commit -m "adding the covid CSV"
[main eef0b9b] adding the covid CSV
 1 file changed, 1948 insertions(+)
 create mode 100644 Provisional_COVID-19_Death_Counts_in_the_United_States_by_County.csv

(base) C:\Users\Curt-RBS\Desktop\NU\NU_MS_EDA_Project>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 27.80 KiB | 1.54 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:robords/NU_MS_EDA_Project.git
   16a6d7f..eef0b9b  main -> main
```
