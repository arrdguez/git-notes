# Git notes

# 1. Perfect commit

    1. Add the right changes!
        Single topic or specific file for a coomit.

    2. Compose a good commit message!

    The perfect coomit Message:
        1. Subject = concise summary of what happened
        2. Body = more detailed explanation
            - What is now different than before?
            - What's the reason for the change?
            - Is there anything to watch out for / anything particularly remarkable?


# 2. Branching Strategies

    A writteng Convention
        Agree on a Branching Workflow in your team
        1. Git allows you to create branches - but it doesn't tell you how to use them!
        2. You neew a written best practice of how work is ideally structured in your team - to avoid mistakes & collitions.
        3. It highly dependes on your team / team size, on your project, and how you handle releases.
        4. It helps to onboard new team members ("this is how we work here")

    Integrationg Changes & Structuring Releases

        1. Mainline Development ("Always Be Integrating")
        2. State, release, and feature branches

    Long-Running Branches
        - exist through the complete lifetime of the project
        - often, they mirror "stages" in your dev life cycle
        - common convention: no direct commits!

        example: develop, production or staging

    Short-Lived Branches (should be deleted after integrated)
        - for new features, bug fixes, refactorings, experiments ...
        - will be deleted after integration
        example: feature, release

# 3. Pull Requests
    A Pull Request invites reviewers to provide feedback before merging.
    Contributing code to other repositories.




# 4. Merge conflicts




# 5. Merge vs Rebase 


    merge: branch workflow
    rebase: straigth line

# Helpufull commands

git config --global --edit


git diff <file>
git add -p <file> # To add only specific file
git push --set-upstream

a. Clean up to solve conflict: k 


