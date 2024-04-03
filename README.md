# Prerequisites For Pull Requests

1. PR namin convention : # ticket no. | ticket title
2. PRs must have clear decsriptions/change list
3. Use atomic commit. [What is atomic-git-commits ?](https://www.aleksandrhovhannisyan.com/blog/atomic-git-commits/)
4. Remove dead/unused and additional commented code.
5. Write impactful comments in your code, don't write redundant and unnecessary comment. Don't explain 'what the code does line by line' instead wrtie 'why this code exists'. Regular epxressions are exception explain your regex clearly.
6. Variable naming: Give concise and just enough decriptive variable names, don't name variable too long to make them descriptive. Use the variable naming best practices in the language you are working for eg: python - snake_case and javascirpt - camelCase.
7. Write simple and readable code.
8. Be consistent in your implementations
9. Follow our style guidelines
    * use `rem` ( border radius are exception )
    * typoghraphy ( aviod giving font styles, just use relevant classes )
    * color libs
    * use [BEM](https://getbem.com/naming/)
10. Declare constant variable in `constant` file, simple rule is when using same data in different place put that into `constant` file so that when we change the data we only required to update that in one place.
11. Before declaring resuable funcitons check if that function exists in helpers/utility files. Declare reusable and generic function in helpers/utility files.
12. To work on a new task or a ticket
    * switch to `dev` branch
    * take pull `git pull`
    * create new branch and work on that branch
13. Avoid using `any` in typescript
14. Before rasing the PR always make build using `yarn run build` or check with the repo maintainer for the `build` cmd.
15. If a project uses `yarn`, it must only contain `yarn.lock`; if a project uses `npm`, it must only contain `package-lock.json`. Both files can't exists in a project at the same time. 
