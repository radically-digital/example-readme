# Name of the Project

> Additional information or tag line

A brief description of your project, what it is used for. (1-2 lines)

<details>
<summary>⭐ Important Notes ⭐</summary>

- Assume that the developer has basic knowledge of git, the language, and following standards. Remember who this document is for.
- Keep all additional documentaion in a `./_DOCUMENTATION` directory
- Try to keep this lean and concise. Anything more than two pages is difficult to maintain.
- Reference over repetition
  - Identify sources of truth and link out to that - if this code has no control of the output (like an IP address) - don't put the IP address in here.
  - Don't use specific details that need to be maintained.

#### Additional Resources

- [.editorconfig file](https://editorconfig.org/)
- [12 factor apps](https://12factor.net/)
- [Frontend Checklist](https://github.com/thedaviddias/Front-End-Checklist)
- [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- [JavaScript Clean Code Guidelines](https://github.com/ryanmcdermott/clean-code-javascript)
- [language specific code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Markdown Reference style link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)
- [nvm](https://github.com/creationix/nvm)
- [Or even the frameworks documentation](https://raygun.com/blog/popular-javascript-frameworks/)
- [Project Guidelines](https://github.com/elsewhencode/project-guidelines)
- [Recommended extensions](https://code.visualstudio.com/docs/editor/extension-gallery#_recommended-extensions)

</details>

## Requirements

- [Docker]

<details>
<summary>⭐ Important Notes ⭐</summary>

- Use packages like [Homebrew], [docker], and [asdf]
- List any global installs here - prefer using [asdf] and [homebrew]
- Do not list frameworks and libraries. These should be included as project dependencies. [See Twelve-factor app - Dependencies](https://12factor.net/dependencies)

</details>

## Installing / Getting started

A quick introduction of the minimal setup you need to get a hello world up &
running.

```shell
commands here
```

<details>
<summary>⭐ Important Notes ⭐</summary>

- Here you should say what actually happens when you execute the code above.
- List any global installs and runtime setting here - prefer using [asdf] and [homebrew]
- This should be simple and concise and repeatable.
- Check with the team if Linux/Windows/Mac support is needed.

</details>

## Developing

### Setting up Dev

Here's a brief intro about what a developer must do in order to start developing
the project further:

```shell
packagemanager install
```

And state what happens step-by-step. If there is any virtual environment, local server or database feeder needed, explain here.

<details>
<summary>⭐ Important Notes ⭐</summary>

- This should represent the day-to-day workflow
- this should not list global dependencies

</details>

### Building (Not always needed)

If your project needs some additional steps for the developer to build the
project after some code changes, state them here. for example:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### Deploying / Publishing

give instructions on how to build and release a new version
In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy your-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

<details>
<summary>⭐ Important Notes ⭐</summary>

- if this uses ci/cd link out to it along with the environments.
- Make use of badges where possible
  - [circleci status-badges](https://circleci.com/docs/2.0/status-badges)
  - [Github Workflow status badge](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge)

</details>

## Versioning

We can maybe use [SemVer](http://semver.org/) for versioning. For the versions available, see the [link to tags on this repository](/tags).

## Configuration

Here you should write what are all of the configurations a user can enter when using the project.

<details>
<summary>⭐ Important Notes ⭐</summary>

- Note configuration is not secrets.
- Use `.env` and `.env.example`.
- Try to refrain from development and production references - let those values come from the env or the build.

</details>

## Tests

Describe and show how to run the tests with code examples.
Explain what these tests test and why.

```shell
Give an example
```

<details>
<summary>⭐ Important Notes ⭐</summary>

- This is sometimes included in the Developing script. This is fine, however if you are working with code that the sysops team is not familiar with, it's a good idea to split this out to make it more convenient for them.

</details>

## Style guide (Optional)

Explain your code style and show how to check it.

<details>
<summary>⭐ Important Notes ⭐</summary>

- Automation is the ultimate authority. Please only list opinionated and non-automated styles here.
- Use tools to automate as much as possible. Note these need to be project dependencies if they are project dependencies.
- Add notes on how to configure common editors if needed.
- Use `.idea`, `.vscode`, and `.editorconfig` configs to help with setup.
- Use precommit and prepush git hooks to automate rules.
- Keep the customization of the tools to a minimum - the defaults are usually good enough.

</details>

## Api Reference

If the api is external, link to api documentation. If not describe your api including authentication methods as well as explaining all the endpoints with their required parameters.

## Database

- Explaining what database (and version) has been used. Provide docker-compose scripts
- Documents your database design and schemas, relations etc...

## Licensing (Optional)

State what the license is and how to find the text version of the license.

<!-- MARKDOWN REFERENCES -->

[homebrew]: https://brew.sh/
[asdf]: https://asdf-vm.com
[docker]: https://www.docker.com/
