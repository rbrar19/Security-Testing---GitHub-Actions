## GitHub Action Explanation

I tried to use the AppScan CodeSweep GitHub Action with:

- HCL-TECH-SOFTWARE/appscan-codesweep@v1.0.18
- hcl-tech-software/appscan-codesweep-action@v2.0.4

But both of them gave an error that said:
> "Action not found"

I checked on GitHub and found that the AppScan Action was removed or made private. Because of this, I was not able to run the scan through GitHub.

---

## Reflection Answer

Using AppScan CodeSweep in VS Code was easier than using Bandit or CodeQL. It showed problems in my code right away when I saved the file. Bandit only works with Python, and CodeQL needs more setup and is harder to use. AppScan was fast and simple, and it helped me find risky code like `eval()`. Even though the GitHub version didn’t work, the VS Code plugin worked well and helped me improve my code.
