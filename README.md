# Git Collaboration: Morgan and Jamie Workflow Documentation

## Project Context
A term of developers is tasked with the resposibility of enhancing a website for Greenwood Community Library.These will help the website to be more engaging and informative.The Website currently includes basic sections like **HOME**,**ABOUT US**,**EVENTS** and **CONTACT US**.Two developers in the same term is asked to add a **BOOK REVIEWS** section and update the **EVENTS** page.

- **Morgan's Task**: Adding the *Book Reviews* section.
- **Jamie's Task**: Update the *Events* pages

## Project Setup

**i**. Create and initialize a repository with a readme.md file and clone it to a local machine.

- Repository name: greenwood-library-website

![img1](./img/img1.png)

- [URL of Cloned Repository](https://github.com/wilfredoamen/green-library-website.git)

![img](./img/img.png)

**ii**. Using VScode editor ensure there are *html* file for home,about_us,events and contact_us. With random content inside the each file.

![img2](./img/img2.png)

Using the following command below stage,commit and push the changes directly to the main branch.

```bash
# Stage Changes
git add .

# Commit Changes with a discriptive message
git commit -m "Discriptive message"

# Push Changes to github repository
git push origin main
```

![img3](./img/img3.png)


## Morgan's Workflow

**1**. Create a branch for Morgan and switch to the new branch **"add-book-reviews"**
by using the command below

```bash
# Create and switch to a branch
git checkout -b add-book-reviews
```
![img4](./img/img4.png)

**2**. Add a new file **"book_reviews.html"** and add a random text content inside the file 

```bash
# Create a new file
touch book_reviews.html
```
![img6](./img/img6.png)

**3**. Stage,Commit and Push Morgan's changes by using the following command below.

```bash
# Add the file the staging area
git add book_reviews.html

# Commit the changes with a discriptive message
git commit -m "Add book review section"

# Push the changes to github repository
git push origin add-book-reviews
```

![img7](./img/img7.png)

**4**. Create a pull request for Morgan's changes

- Open a web-broswer and navigate to the github repository.[Github-Url](https://github.com/wilfredoamen/green-library-website/tree/add-book-reviews)

![img7b](./img/img7b.png)

- Switch to Morgan's branch by clicking on the branch dropdown menu and select add-book-reviews branch, which is in this case Morgan's branch. After switching to morgan's branch click the dropdown menu *Contribute* and select *Open pull request*

![img8](./img/img8.png)

- After clicking the dropdown menu Contribute, followed by the Open pull request. These will automatically select the main project's branch as the base and Morgan's recently pushed branch "add-book-reviews" as the compare branch. Since everything look good, after providing a title and description for the pull request Click "*Create pull request*" to create a pull request.


![img9](./img/img9.png)

**5**. Review and Merge Morgan's Pull Request

Since the pull request is created and now visible to a team member who can review and merge Morgan's changes. The team member reviewing Morgan's changes approved and merges the pull request, since the term agrees with the changes.

![img10](./img/img10.png)

![img11](./img/img11.png)



## Jamie's Workflow

**1**. Create a branch for Jamie and switch to the new branch **"update-events"** by using the command below


```bash
# Create and switch to a branch
git checkout -b update-events
```

![img12](./img/img12.png)

**2**. Pull the latest changes from the main branch into the update-events branch to ensure Jamie's branch starts with the latest changes, reducing conflicts.

```bash
# Pull latest changes
git pull origin main
```
![img-pull](./img/img-pull.png)

**3**. Add a new file **"events.html"** and add a random text content inside the file 

```bash
# Open and update the events file
nano events.html
```

![img12a](./img/img12a.png)


**4**. Stage,Commit and Push Jamie's changes by using the following command below.

```bash
# Add the file the staging area
git add events.html

# Commit the changes with a discriptive message
git commit -m "updated the events.html file"

# Push the changes to github repository
git push origin update-events
```

![img13](./img/img13.png)


**5**. Pull the latest changes from the main branch into the update-events branch before creating PR, to ensure it reflects the latest mian state,making the review and merge process smoother.

```bash
# Pull latest changes
git pull origin main
```
![img-pull](./img/img-pull.png)

**6**. Create a pull request for Jamie's changes

- Open a web-broswer and navigate to the github repository.[Github-Url](https://github.com/wilfredoamen/green-library-website/tree/update-events)

![img7b](./img/img7b.png)

- Switch to Jamie's branch by clicking on the branch dropdown menu and select add-book-reviews branch, which is in this case Jamie's branch. After switching to Jamie's branch click the dropdown menu *Contribute* and select *Open pull request*

![img14](./img/img14.png)

- After clicking the dropdown menu Contribute, followed by the Open pull request. These will automatically select the main project's branch as the base and Jamie's recently pushed branch "update-events" as the compare branch. Since everything look good, after providing a title and description for the pull request Click "*Create pull request*" to create a pull request.


![img15](./img/img15.png)

**7**. Review and Merge Jamie's Pull Request

Since the pull request is created and now visible to a team member who can review and merge Jamie's changes. The team member reviewing Jamie's changes approved and merges the pull request, since the term agrees with the changes.

![img16](./img/img16.png)


![img17](./img/img17.png)





