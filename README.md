# CITS5551_BookInventory
Prototype ML-powered system for automated book inventory management, pricing, and online listing.

### Team Rules
1. Create a new branch when a new feature is introduced.
2. Include detailed commit messages.
3. Create issues first, assign them, then create PR.
4. Do not merge to main at first instance, first create a PR
5. Create a PR and ensure 2 other people review it.
6. Keep documentation up to date and comprehensive
7. Write maintainable modular code


### GitHub Team Workflow Rules

This document defines the GitHub collaboration guidelines for our project. All team members should follow these rules to keep the repository organised, stable, and easy to maintain, while encouraging open communication and collaboration within the team.

#### 1. Main Branch Protection
- Do **not push directly** to the `main` branch.
- The `main` branch should always remain **stable and runnable**.
- All changes must go through a **Pull Request (PR)** before merging.

#### 2. Branch Workflow
Each task must be done in a **separate branch**.

Branch Naming Convention:
- `feature/...` → New features
- `fix/...` → Bug fixes
- `docs/...` → Documentation updates
- `refactor/...` → Code improvements
- anything else ??
  
#### 3. Sync with Main Before Starting Work
Before beginning work, update your local repository to reduce merge conflicts:

```bash
git pull origin main
```

#### 4. Commit Message / Inline Comment Guidelines

- Write clear and meaningful commit messages. A good commit message should explain what was changed and why. 

- Add brief inline comment wherever required to help other team members understand your work.

#### 5. Pull Request Rules

Before merging changes:
```
1.	Create a Pull Request
2.	Provide a clear title and description
3.	Request at least two team member review
4.	Wait for approval before merging
```
No one should merge unfinished or unreviewed code.

#### 6. Pull Request Template

Description
```
- What was changed?
- Why was it changed?
- Anything reviewers should test or check?
```

#### 7. Code Review Guidelines

When reviewing a Pull Request, check if:
```
- The code runs correctly
- The logic is clear and readable
- The code follows the project structure
- It does not break existing functionality
- There are unnecessary files or changes
```
Reviews should be constructive and respectful :)

#### 8. Testing Before Pushing

Before pushing code:
```
- Ensure the code runs successfully
- Test the changes you made
- Confirm that existing features still work
- Remove debug prints or temporary files
```

#### 9. File Organisation

Keep the repository organised:
```
- Use meaningful file names
- Place files in appropriate folders
- Avoid duplicate or unnecessary files
- Do not upload temporary files or personal notes
```

#### 10. Use .gitignore

The following should not be committed:
```
- Virtual environments
- Cache files
- Build files
- System files
- Large datasets (unless required???)
```
#### 11. Security Rules

Never upload sensitive information such as:
```
- API keys
- passwords
- tokens
- private credentials
- confidential client data
  ```
#### 12. Use GitHub Issues for Task Tracking

Whenever possible, create a GitHub Issue for tasks.

#### 13. Communication Guidelines

Before starting major work:

- Inform the team what you are working on if the task was not discussed/assigned in the meeting (then create Issue)
- Avoid editing the same files simultaneously without coordination
- Discuss major design or structural changes with the team

#### 14. Team Collaboration Guidelines

To maintain a supportive and productive environment, we encourage the following:

- **Share your ideas freely.** If you think something could improve the project, feel free to suggest it.
- **Ask for help when needed.** If you are struggling with something, reach out to the team early so we can solve it together.
- **Be open to feedback.** Suggestions during code reviews are meant to improve the project, not criticise individuals.
- **Support each other.** If you notice a teammate having difficulty, offer help where possible.
- **Communicate clearly.** Keep the team informed about what you are working on or any issues you encounter.
- **Respect everyone’s contributions.** Every team member’s input is valuable.

*Team Agreement*

By contributing to this repository, team members agree to:
```  
- Work using branches
- Keep the main branch stable
- Write clear commit messages/comment
- Use Pull Requests for merging
- Review each other’s work
- Maintain a clean repository
- Communicate major changes
- Share ideas or ask for help
- Protect sensitive information
- Respect everyone
```
