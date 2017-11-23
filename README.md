# **INSTRUCTION**
In this repository, you can find a script `cookie_cutter_template.sh` that produces an organized project template.

This script was created in November 2017 after my thorough consideration for the cookie-cutter organization of many data analysis projects publicly available on Github.

### Before running the script:
0. If you haven't done so, [create a **git repository**](https://help.github.com/articles/creating-a-new-repository/) where you will store your project in.

1. Open your **terminal** or its equivalence (e.g. Git Bash, Anaconda Prompt, Command Prompt) on your local computer.

If you don't have anything like this, please install one. I recommend Git Bash since I'm using it and find it very easy to use.

2. Clone your **git repository** to your local laptop.

For example, I want to save this repository in my desktop...

```
cd desktop
git clone https://github.com/username/projectname.git
```

### Getting the source:
[**Clone**](https://help.github.com/articles/cloning-a-repository/) this repository to your local computer.

### Run:
Run the script in your **terminal**.

```
bash cookie_cutter_template.sh
```
While running the script, you will be prompted with some questions.

1. What is the path of your directory?

Set path to your project repository created in the beginning.

Path is set like when you use `cd` command in `terminal`. If you don't know what `cd` does, [read more](http://www.rapidtables.com/code/linux/cd.htm). Follow the way they set path, but don't include command `cd` in your answer.

2. What do you want to name your project?

Type in a descriptive name for your project.

Ex: predict_sales_2018, ab_test_new_menu

3. What license you want to use?

I pre-set options for: MIT License, Apache License 2.0 and No License.
You can [read more](https://choosealicense.com/) on which license you want to choose.

If you choose a different license than the 2 I pre-set, you can choose `3` - No License when prompted with this question. Then paste the license you desire to `LICENSE.md`.

### Output:
If the script is run successfully, you can expect to see a project organized like this:

```
| project_name
| -- README.md
| -- LICENSE.md
| -- CITATION.md
| -- data  
|    -- raw_data
|    -- cleaned_data
|    -- data_for_analysis
| -- src  
| -- analysis
| -- results
| -- graphs
|    -- observatory_analysis_graph
|    -- report_graph
| -- reports
| -- other
```
