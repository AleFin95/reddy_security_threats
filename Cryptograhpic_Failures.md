# Security Threats

You're tasked with creating a `.md` file containing specific information about your **Security Threat**. 

Here are some general guidlines about how to structure your `.md` files. 

One person per group should 'scribe' for the rest of the team.

- Main Section: What is the **Security Threat**
    - How does it work
    - Who is the attack usually carried out by
    - What issues / problems does it cause 
    - What mitigations exist

You should **fork** from this: [repository](https://github.com/emilesherrott/reddy_security_threats) then conduct your research and add your information as you go. 

When you've finished then push your code back to your remote repositories and make a PR into the original repository. 


## Making a PR

1. Fork & Clone
    - Make sure you're on your fork, you'll see your username on Github next to the repository name. 
    - Create a directory to clone to repository into. 
    - Click the green 'code' button and use `git clone` to add the repository locally to your machine. 

2. Set the original repository as the **upstream**
    - `git remote add upsteam git@github.com:emilesherrott/reddy_security_threats.git`
    - You should be able to run: `git remote -v` and see the **origin** link to your owned repository and the **upstream** being mine. 

3. Pull any changes from the **upstream** with `git pull upstream main`
    - Then make any changes to the files you're working on in VSCode. 

4. Stage / Commit / Push your changes
    - `git add .`
    - `git commit -m "<message>"`
    - `git push`

5. Make a **Pull Request** 
    - Locate your repository and make a Pull Request back to the original (upstream) version of code. 