# devops-lab
## This repo is a storage for devops practise tasks
### Pre-requisities
1. Git installed on your local machine
2. SSH key added to your git account ([Add SSH key to your GitHub Account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account))
3. All topic based requirements will be listed in the topic README.md
### How to work with repositpry
1. Clone this repository to your local machine
2. Create your personal branch. `git checkout -b <name>_<surname>`
3. Your work should only be stored in your own branch. Do not publish your code to main or make any pull requests to main
4. Each time you starting a new lesson please make a subbranch from your own branch
```
git checkout <name>_<surname>
git checkout -b <name>_<surame>_lesson_<lesson_number>
```
Do all your work in this subbranch and then make a pull request to your branch. docs here [Creating a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
>***Be sure you are not making pull request agains `main` branch***
5. Add your mentor as a reviewer to your pull_request [Adding reviewers to Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review)

### This course contains Lessons that will guide you through next topics

| Lesson Number |      Lesson Name       | Lesson Description                                                                                                                                                                             |
|:-------------:|:----------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       1       |         Python         | In this section you will learn basics of python such as data types, functions, classes                                                                                                         |
|       2       |         Docker         | In this section you will learn containerized application principles and will get a practical experience with most popular container engine **Docker**                                          |
|       3       |          AWS           | In this section you will learn the most popular cloud services, provided by AWS. You will get practical experience of using them                                                               |
|       4       | Infrastructure as Code | In this section you will learn principles of infrasstructure as a code flow. You will work with a tool called [**Terraform**](https://www.terraform.io)                                        |
|       5       |       Kubernetes       | In this section you will learn principles of container orchestration tool called [**Kubernetes**](https://kubernetes.io). Also you will learn some of it's plugins and applicable technologies |