# Run Github Actions locally

## Description

The following documentation outlines how to run Github Actions locally. It requires the library `Act`, In order to run your workflows locally, it must run a container for the runner defined in your workflow file, which currently only works with `Ubuntu` workflows.

## Act, Run Github Actions locally

To use `Act`, we need to install it via Homebrew with the following command:

```bash
brew install act
```

Then we need to start Docker and then go to the root of a project we want to use Act on and open up your terminal and run one of the following commands.

List the actions for the default event:

```bash
act -l
```

Run a specific job, to find the name of the job, go to the workflow and look for the word `jobs` and the word underneath it should be the name of the job you need to pass to `Act` as a parameter, as in the example below:

```yml
jobs:
  test:
```

```bash
act -j test
```

If you are still having issues, refer to the following documentation that `Act` provides [link](https://github.com/nektos/act).