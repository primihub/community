Welcome to the PrimiHub community!

We value any kind or size of the contribution. If you find a typo in the documentation, or have made improvements, do not hesitate to submit a GitHub pull request. We have many open-source projects. Please feel free to look at the following table.

| Name | Description | Skills |
|---|---|---|
| [PrimiHub](https://github.com/primihub/primihub) | Hyper Multi-Party computing platform | C++ for the core </br> Python for the SDK |
| [HEhub](https://github.com/primihub/hehub) | A library for homomorphic encryption and its applications | C++ |
| [PrimiHub Platform](https://github.com/primihub/primihub-platform) | Hyper Multi-Party computing Application | Spring Boot as the backend </br> Vue as the frontend </br> Maven as the build tool |
| [Documentation](https://github.com/primihub/primihub-docs) | The official document of PrimiHub | Powered by [Docusaurus 2](https://docusaurus.io/) |

## Development workflow

Below is a common contribution guide in the PrimiHub community:

### Step 1 Fork the project repository

Click the `Fork` button near the top of the project page. Such as click [here](https://github.com/primihub/primihub/fork) to fork the [PrimiHub repo](<https://github.com/primihub/primihub>). For more details, see [this](https://docs.github.com/en/get-started/quickstart/fork-a-repo) guide.

### Step 2 Clone the fork of the repository

For example, clone the fork of the PrimiHub repo by running the following command

```shell
git clone git@github.com:your-account/primihub.git # add --depth 1 if your connection is slow
cd primihub
```

### Step 3 Add remote to the main repository

This saves a reference which you can keep your repository synchronized with the latest changes. For example, run the following command to add the `upstream` remote to the [PrimiHub repo](<https://github.com/primihub/primihub>).

```shell
git remote add upstream git@github.com:primihub/primihub.git
```

To check the remote is configured correctly, run `git remote -v`

### Step 4 Build the project from source (if necessary)

Follow [this](https://docs.primihub.com/docs/advance-usage/start/build/) doc to build the Primihub project from source. Then [install](https://docs.primihub.com/docs/advance-usage/python-sdk/install/) the Python dependencies. Skip this step if necessary, e.g., document contribution.

### Step 5 Develop the feature and push your work

First, create a feature branch to hold your development changes.

```shell
git checkout -b my_feature
```

Then, start making changes. When you’re done editing, add changed files using `git add` and then `git commit` to record your changes.

```shell
git add modified_files​
git commit -m "description of the changes"
```

It is often helpful to keep your local feature branch synchronized with the latest changes of the main repository.

```shell
git fetch upstream/develop​
git merge upstream/develop
```

You might need to solve the conflicts, refer to [this](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line) doc if needed.

Finally, push the changes to your GitHub account.

```shell
git push -u origin my_feature
```

### Step 6 Open a new pull request

Follow [these](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) instructions to create a pull request from your fork. Please provide a readable PR title and detailed descriptions.

## Join Us

* [Twitter](https://twitter.com/OpenPrimi)
* [Gitter](https://gitter.im/primihub/community)
