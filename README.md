# Welcome to CBE 67701!

Please check the Sakai website for useful links including the Zoom meeting information.

## Goals and Expectations

The overall goal of this reading group is to learn about uncertainty quantification with an eye to actual implementations and examples. We have a diverse classes with wide-ranging experiences and prior knowledge levels. Most people (including the instructors) will not fully appreciate and understand each sentence of each chapter. Instead, we recommend approaching each chapter with three questions in mind:
1. What are the overall concepts and how do they relate?
2. How could I apply one of these methods to a useful (engineering) problem?
3. What 1 or 2 clarifying questions should I ask in the class discussion to best advance my understanding of the two prior questions?

Everyone is expected to (attempt) to read each chapter and contribute at least one question per week on the class Google Doc (see Sakai for link). 

## Chapter Examples

Each student will be assigned (see class Google Doc) one chapter to prepare a minimum working example to demonstrate an important method or application. Please keep these examples simple; not only does too complex of an example take a long time to prepare and debug, but the extra details may distract from the main message.

### Step 1: Set Example Scope

Need inspiration? Ask yourself:
- Is there an exisiting example or figure in the textbook I would like to learn how to reproduce?
- Can I construct a (very simple) application related to my research to try a method in the chapter? (Caution: This might take longer than you think.)

Once you have sent the scope of the example, outline the main steps of the analysis on paper. Some people refer to this as writing pseudocode.

### Step 2: Find the Corresponding Example File

The schedule will indicate in you are assigned example **01** or **02** for each chapter. Find the corresponding file `/notebooks/XX.0Y-An-Example.ipynb` in the class GitHub repository where ``XX`` is the chapter number and `0Y` is either `01` or `02`. This is the file you should edit. Do not edit the corresponding files in the `/docs` folder. The files in the  `/docs` folder will be automatically generated with proper formating.

### Step 3: Create a Branch in GitHub

By creating a branch, you'll be able to work independently of your classmates. Tip: Give the branch a meaningful name such as your username or the chapter and example number.

### Step 3: Create and Test Your Example

Now for the fun part: create and test your example. (See recommendations below in software setup.)

Styleguide:
- Try to break your example into a few sections. Remember section headers start with `##` in markdown cells.
- Typeset any equations for the example in a markdown cell using LaTeX. Alternately, you may write the equations on paper, take a photo, and embed in the notebook.
- Place all figures in `/notebook/figures/` and all data in `/notebooks/data/`.
- Do not include section or subsection numbers. Those will automatically be added.

As you work, periodically push updated to your branch.

### Step 4: Create a Pull Request

Once your example is ready, create a pull request to merge into the master branch. Email Prof. Dowling if you need help.

### Step 5: Run nbpages to Publish to the Class Website

Please email Prof. Dowling by 11am EDT the day of your presentation, if not earlier. He will publish your notebook to the class website. Why the hard time deadline? There is a significant delay in updating the cache on GitHub pages.
