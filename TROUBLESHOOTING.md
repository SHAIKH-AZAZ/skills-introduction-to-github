# Troubleshooting Guide

This guide helps you resolve common issues you might encounter while completing the "Introduction to GitHub" course.

## Common Issues

### Issue: Actions workflow not updating to the next step

**Symptoms:**
- You completed a step, but the README hasn't updated
- The step number in `.github/steps/-step.txt` hasn't changed

**Solutions:**
1. **Wait a moment**: GitHub Actions can take 20-60 seconds to run. Wait a bit longer and refresh the page.
2. **Check Actions tab**: Go to the "Actions" tab in your repository to see if the workflow is running or if it failed.
3. **Verify your work**:
   - Step 1: Did you create a branch named exactly `my-first-branch`?
   - Step 2: Did you create a file named `PROFILE.md` in the `my-first-branch` branch?
   - Step 3: Did you open a pull request from `my-first-branch` to `main`?
   - Step 4: Did you merge the pull request?

### Issue: Branch not created

**Symptoms:**
- You tried to create a branch but can't find it
- You're still on the `main` branch

**Solutions:**
1. Check that you typed the branch name correctly: `my-first-branch` (all lowercase, hyphens, no spaces)
2. Make sure you clicked "Create branch: my-first-branch" button
3. Look for the branch dropdown menu to verify the branch was created
4. Try refreshing the page

### Issue: Can't find "Create new file" option

**Symptoms:**
- The "Add file" dropdown is missing or grayed out
- You can't create a new file

**Solutions:**
1. Make sure you're on the correct branch (`my-first-branch`, not `main`)
2. Check the branch dropdown at the top of the file list
3. Try refreshing the page
4. Ensure you're logged into GitHub

### Issue: Pull request not appearing

**Symptoms:**
- You created a file but don't see a "Compare & pull request" button
- Can't find your pull request in the Pull Requests tab

**Solutions:**
1. Make sure you committed your changes (not just created the file)
2. Navigate to the "Pull requests" tab manually and click "New pull request"
3. Verify your base branch is `main` and compare branch is `my-first-branch`
4. Check that you're in the correct repository

### Issue: Changes not committed

**Symptoms:**
- You created a file but it's not showing up in your branch
- The workflow didn't trigger

**Solutions:**
1. After creating/editing a file, make sure you clicked "Commit changes" button
2. Verify the commit message was added
3. Check that you committed to the correct branch
4. Go to the file list and verify the file appears there

### Issue: Merge button is disabled

**Symptoms:**
- The "Merge pull request" button is grayed out
- You can't merge your pull request

**Solutions:**
1. Wait for GitHub Actions to complete (look for the green checkmark)
2. Check if there are merge conflicts that need to be resolved
3. Ensure you have the necessary permissions (you should in your own repository)
4. Wait a few moments and refresh the page

## GitHub-Specific Issues

### Issue: Repository not created from template

**Symptoms:**
- Your repository doesn't have the same files as the template
- Workflows are missing

**Solutions:**
1. Go back to the course start page and click "Start course" again
2. Make sure you clicked "Create repository from template" not just "Fork"
3. Ensure the template was `skills/introduction-to-github`

### Issue: Actions disabled

**Symptoms:**
- Workflows aren't running
- No activity in the Actions tab

**Solutions:**
1. Go to Settings > Actions > General
2. Ensure "Allow all actions and reusable workflows" is selected
3. Make sure Actions are enabled for your repository

### Issue: Permission errors

**Symptoms:**
- Getting 403 or permission denied errors
- Can't push changes or create branches

**Solutions:**
1. Make sure you're logged into GitHub
2. Verify you're the owner of the repository (check the repository URL)
3. Try logging out and logging back in

## Still Having Issues?

If none of these solutions work:

1. **Check GitHub Status**: Visit [githubstatus.com](https://www.githubstatus.com/) to see if there are any ongoing issues
2. **Ask for help**: Post in the [Skills Discussions](https://github.com/orgs/skills/discussions/categories/introduction-to-github)
3. **Review the docs**: Check the [GitHub Docs](https://docs.github.com) for more detailed information
4. **Start fresh**: If all else fails, you can delete the repository and start over by clicking "Start course" again

## Tips for Success

- **Read carefully**: Make sure you follow each step exactly as written
- **Take your time**: There's no rush - understand each concept before moving on
- **Experiment**: It's your repository, so feel free to try things out
- **Use multiple tabs**: Keep the instructions open in one tab while working in another
- **Check your spelling**: Branch names and file names must match exactly

---

Need more help? Don't hesitate to ask in the [discussions](https://github.com/orgs/skills/discussions/categories/introduction-to-github)!
