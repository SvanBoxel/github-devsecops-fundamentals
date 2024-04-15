<!-- markdownlint-disable MD033 -->

<h1 align="center">GitHub DevSecOps Fundamentals</h1>

<p align="center"><a href="https://github.com/igwejk">@igwejk</a> • <a href="https://github.com/mouismail">@mouismail</a></p>

<p align="center">
  <a href="https://githubuniverseworkshops.github.io/github-devsecops-fundamentals/prerequisites">Prerequisites</a> •
  <a href="https://githubuniverseworkshops.github.io/github-devsecops-fundamentals/#resources">Resources</a> •
  <a href="https://githubuniverseworkshops.github.io/github-devsecops-fundamentals/#learning-objectives">Learning Objectives</a>
</p>

<p align="center">
Goto <a style="font-weight=bold" href="https://githubuniverseworkshops.github.io/github-devsecops-fundamentals">:eyes: workshop site</a>
</p>

## Running the Application in Codespaces

To run this application in Codespaces, follow these steps:

1. Ensure you have a GitHub account and are logged in.
2. Navigate to the repository and click on the "Code" button, then select "Open with Codespaces" > "New codespace".
3. Codespaces will prepare your development environment, which might take a few minutes.
4. Once the environment is ready, the application will automatically start thanks to the `postAttachCommand` in `.devcontainer/devcontainer.json`.
5. You can access the application by clicking on the forwarded port in the Ports panel.

### Accessing and Using Forwarded Ports

To access and use forwarded ports within Codespaces:

1. Open the Ports panel in the Codespaces environment.
2. Look for the port number specified in `.devcontainer/devcontainer.json` (e.g., 8080).
3. Click on the "Open in Browser" icon next to the port to access the application.

### Troubleshooting Tips

If you encounter issues setting up or running the application in Codespaces, consider the following tips:

- Ensure your Codespaces environment has finished setting up before trying to access the application.
- Check the `.devcontainer/devcontainer.json` file for any configuration errors.
- If the application does not start automatically, open a terminal in Codespaces and run the `postAttachCommand` manually.
- For issues related to port forwarding, verify the port configuration in `.devcontainer/devcontainer.json` and try restarting the application.

