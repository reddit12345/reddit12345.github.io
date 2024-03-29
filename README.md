# Hosting a Resume on Github
# About
To describe the practical steps of how you host and format your resume on Github to share your professional portfolio with future employers and other collaborative individuals.

# Prerequisites
- A resume in markdown format
- A markdown editor
- (Optional) Github pages or any other static site generator
- README file (in Markdown format)

# Instructions

![Sample_Resume](sample-resume.gif)

## 1. Prepare your resume
#### Etter's Principle: Structured Content
- Using a lightweight Markdown editor to write your resume and your README file is essential to organizing our document which would also provide ease-of-use and efficiency.

### Writing a Markdown file
1. Firstly, you have to know your target audience as it is important to set the tone of your document.
2. Structure the content of your resume by placing appropriate headings (Use **#** followed by the title of the header)
3.  Use lists (**-**) and numbers ("**1**") with an appropriate heading to let readers follow along the instructions more clearly.
4. Use easy-to-understand words to broaden your target audience and therefore give clarity and conciseness to what you want to say.
## 2. Use a Distributed Version Control System
#### Etter's Principle: Version Control
-   Making use of a distributed version control system (DVCS) is paramount in software development. This tool is incredibly powerful - offering scalability, auditing, collaboration, and recovery features essential for successful software development endeavors.
### Creating a Github repository
1. On Github home page, click on **Home -> Repositories.**
2. On the repositories section, click **New**.
3. Give the repository a name, preferably, "***username*.github.io**". Optionally, you may add a description.
4. Set it as public, then click **Create Repository**.
### Uploading files
1. To upload existing files, click on "**Add File**" -> "**Upload Files**".
2. Find the necessary files needed to be placed in the repository.
3. Once all files are ready to be committed, click on "**Commit Changes**".

## 3. Build a Static Website
#### Etter's Principle: Accessibility
- Static site generators offers a good way to build documentation websites easily. Thus, letting users to share their documents, such as resumes, portfolios, and other things to the internet.

### Enable Github Pages
1. Under the **Repository Settings**, select the branch where your resume is located.
 
### Hosting the resume in a static website
1. Rename your resume to "**index.md**", this lets Github run the resume as the main page of the static site using Jekyll.
2.  A pending symbol will be shown right next to the repository name after committing.
3. Refresh the page until you see that the pending symbol has turned into a green check mark.
4. Visit the site via ***username*.github.io** (Change *username* to whatever is the name of your repository).

## 4. Resume Customization and Update
#### Etter's Principle: User-focused
- The appearance and content of your resume should adhere to the expectations of your target audience.

### Updating your Resume
1. Go to the repository where your resume is located.
2. Click on the name of the resume file.
3. Click the pencil logo near the right-hand side of the web page.
4. Update necessary things on your resume.
5. Click on **Commit Changes...** once you are finished.


# More Resources
## Adding GIFs to Resume
1. On Github, go to your repository where your resume is located.
2. Upload the .gif file you want to add to that repository.
3. On your resume add in:
`![Any Text Here](file-name.gif)`

# Authors and Acknowledgements
- Sachin Bhatt
- Benedict Agupitan

# FAQs

### 1. Why is my static site not found?
- Make sure that your **username** of your Github account is the same as the ***username*.github.io**
- Check any spelling or grammatical errors and try again.
- If the site is currently being built, you may need to wait for a few seconds and refresh the page.

### 2. Why is my GIF not showing in my resume?
- Check if your .gif file is correctly located in the appropriate branch of your repository. If it's in another repository, make sure to add the root directory before the name of the .gif file
- Make sure that the code is typed correctly.

### 3. How does Github automatically know which file to use to show in the static site?
- Github is powered by Jekyll. Jekyll is a static-site generator where Markdown file formats are converted into html files

### 4. Why is Markdown better than a word processor?
- Markdown offers several advantages compared to a word processor. One of the many advantages of a Markdown is its ability to be consistent across multiple platforms and is regarded as a standard. It is also lightweight and uses simple syntax to emphasize readability and user-centricity.


 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI2Mjc0MzM4MCwtMTI5MzEyODgxNCwxMz
gxMDgzNzk4LDIwNzI5Nzc3MjMsMTAwNjQzMTgyMywyMTM4OTQ2
Mjc1LC00MTM3MzA4MzcsMTY3NzE5MTgyNCwyMDY0OTM2NjUzLD
k2MjQyNzUwNCwzNTEzMjQxODEsMTIxNzUyODYwOSwxMDc5MjIz
MDksLTY0MjQyMDA5NywxNjYyMzIxOTQ0LC0zMjkzNDU1NjksLT
ExNjkwMjM4MDEsMTUzNzczMTkzOSwxODIwNjYzNjI2LC0yMDg4
NzQ2NjEyXX0=
-->
