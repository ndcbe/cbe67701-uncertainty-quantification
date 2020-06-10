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

You should aim to spend 5 to 10 minutes presenting your example and about 5 minutes answering questions.

### Step 1: Set Example Scope

Need inspiration? Ask yourself:
- Is there an exisiting example or figure in the textbook I would like to learn how to reproduce?
- Can I construct a (very simple) application related to my research to try a method in the chapter? (Caution: This might take longer than you think.)
- Can I find a popular Python package that implements one of the methods from the chapter? If so, does the documentation for the package have an example I could turn into a brief mini-tutorial for my classmates?

Tip: Email Prof. Kantor (jeff@nd.edu) if you need help installing a custom package on Google Colab.

Tip: Some examples from Prof. McClarren are available [here](https://github.com/ndcbe/cbe67701-uncertainty-quantification/blob/master/UQ_Notebooks.zip). Examples (electronic supplemental materials) for Chapters 2, 3, 4, 6, 7, 9, 10, and 11 are also available on Sakai or through the publisher's website.

Once you have set the scope of the example, outline the main steps of the analysis on paper. Some people refer to this as writing pseudocode. It is really important, especially when you are learning something new.

### Step 2: Find the Corresponding Example File

The schedule will indicate in you are assigned example **1**, **2**, or **3** for each chapter. Find the corresponding file `/notebooks/XX.0Y-Contributed-Example.ipynb` in the class GitHub repository where ``XX`` is the chapter number and `0Y` is `01`, `02`, or `03`. This is the file you should edit. **Do not edit** the corresponding files in the `/docs` folder. The files in the  `/docs` folder will be automatically generated with proper formating. This is important.

After locating `XX.0Y-Contributed-Example.ipynb`, download it to your local computer.

### Step 3: Upload Your File To Colab

We recommend creating your example in Google Colab. This is a free, cloud-based Python environment. That means you do not need to install any special software on your computer. Here are the steps:
1. Navigate to https://colab.research.google.com/
2. Choose **File --> Upload Notebook** in the menu
3. Upload the notebook you obtained from the previous step
4. Save a copy in Google Drive

Tip: While Colab does support limited integration with GitHub, the current interface is clunkly. You are welcome to try it for yourself, but you have been warned...

### Step 4: Create and Test Your Example

Now for the fun part: create and test your example.

Styleguide:
- Try to break your example into a few sections. Remember section headers start with `##` in markdown cells.
- Typeset any equations for the example in a markdown cell using LaTeX. Alternately, you may write the equations on paper, take a photo, and embed in the notebook.
- Place all figures in `/notebook/figures/` and all data in `/notebooks/data/`.
- Do not include section or subsection numbers. Those will automatically be added.

Graduate students Xian Gao, Elvis Eugene, Bridgette Befort, and Kanishka Ghosh all have experience using Google Colab. Prof. Kantor (jeff@nd.edu) is also a great resource.

### Step 5: Create a Branch in GitHub

On GitHub, find the drop down box containing "Branch:".

![](/notebooks/figures/create-branch.png)

To create a branch, type a meaningful name such as your username or the chapter and example number into the field.

### Step 6: Upload your .ipynb File

Select your new branch from the dropdown menu. Then navigate to the `/notebooks` folder and choose the **Upload files button**.

![](/notebooks/figures/upload-files.png)

Note: Advanced users are welcome to modify Steps 3, 4, 5, and 6 to instead edit on their local machine. We recommend using [anaconda](https://www.anaconda.com/) and your favorite git desktop client (or the command line interface). 

### Step 7: Create a Pull Request

Once your example is ready, create a pull request to merge into the master branch. After uploading the new notebook file to your branch, you should see an orange/yellow box with your branch name.

![](/notebooks/figures/pull-request1.png)

Choose **Compare & pull request**.

This should take you to a screen with the title **Open a pull request**:

![](/notebooks/figures/pull-request2.png)

Make sure you see **master <-- your branch name**. Then add a descriptive comment (what did you change) and click **Create pull request**.

Email Prof. Dowling after you create your pull request. You **must do this by 11am EDT the day of your presentation** at the latest.

### Step 8: Run nbpages to Publish to the Class Website

Prof. Dowling will publish your notebook to the class website. Why the time deadline (11am)? There is a significant delay in updating the cache on GitHub pages.
