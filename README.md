In this project, I focused on practicing Git version control by creating a simple HTML file and
managing multiple feature branches. The first step was initializing the repository and setting up
the "main" branch as the base. I then created two separate feature branches: "feature/header" and 
"feature/footer". On each branch, I implemented the reaspective feature - adding a header and 
a footer - and commited the changes independently. After, I intentionally added the footer in
the "feature/header" branch as well, creating a conflict with the footer already present in 
"feature/footer". When I attempted to merge "feature/header" into "main" after merging "feature/footer",
Git flagged a merge conflict in "index.html". I examined the conflicting sections and mannually
edited the file to combine both features, ensuring that the header and footer were both present.
After resolving the conflict, I staged and commited the changes to finalize the merge. Using
the "push origin main" command, I uploaded the commit into the remote repository.