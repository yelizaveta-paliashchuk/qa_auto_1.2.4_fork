# This is task for you

<details>
  <summary>Click me or don't</summary><br/>
  do you like this markdown feature? :) <br/>
  ok, but let's proceed with the tasks
</details>

**Let's get started**

1. Do the fork of this repo to your github (yes, learn what is _fork_) and clone this your new repo to your local
2. Add 3 new .md files using for each of them separate commit (call them "first", "second", "third" to check it more easier later)
3. Learn how to use `git reset` ([help](https://git-scm.com/book/ru/v2/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%A0%D0%B0%D1%81%D0%BA%D1%80%D1%8B%D1%82%D0%B8%D0%B5-%D1%82%D0%B0%D0%B9%D0%BD-reset))
4. Try to reset your commits:

- first, check git logs using a specific command and get commits id's (preferably short versions of them)
- execute `git reset --soft bc9cfc7` (just replace the commit id with your second commit id) - you reset current HEAD to the second commit!
- check git logs (using git command) and check what happened with your code
- execute `git reset --soft hg455kj` (replace the commit id with your third commit id) - you changed back the HEAD to the third commit!
- check git logs (using git command) and check what happened with your code (magic!)
- do the same using 2 other parameters for `git reset` command
- write down and share with us what you have noticed in the code after using each of these 3 parameters
- save logs for all theese actions into a file and share it with us!

---

# This is my answer

1. **Executing `git reset --soft`command**

- after the execution of the `git reset --soft` command with my second commit's id, I had noticed that the HEAD was reset to the second commit, but third file was still staged, ready to be commited.
- after executing `git log` I had noticed that the commit with the third file had gone from the logs.
- after the execution of the `git reset --soft` command with my third commit's id, I had noticed that the HEAD was reset back to the third commit, and third file is commited again.
- after executing `git log` I had noticed that the third commit was back in the logs.

2. **Executing `git reset` mixed command.**

- after the execution of the `git reset` command with my second commit's id, I had noticed that the HEAD was reset to the second commit, and the third file became untracked.
- after executing `git log` I had noticed that the commit with the third file had gone from the logs.
- after the execution of the `git reset` command with my third commit's id, I had noticed that the HEAD was reset back to the third commit, and third file is commited again.
- after executing `git log` I had noticed that the third commit was back in the logs.

3. **Executing `git reset --hard`command.**

- after the execution of the `git reset --hard` command with my second commit's id, I had noticed that the HEAD was reset to the second commit, and the third file was removed from the project.
- after executing `git log` I had noticed that the commit with the third file had gone from the logs.
- after the execution of the `git reset --hard` command with my third commit's id, I had noticed that the HEAD was reset back to the third commit, and third file was back in the project and commited.
- after executing `git log` I had noticed that the third commit was back in the logs.

The link to the logs file can be found [here](logs(1.2.4).md)
