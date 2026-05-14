# Introduction

The Atomic-Learning organisation includes a variety of images which are designed to be used in Codespaces supporting a content page. By selecting a relevant Codespace, you can use an image which will load faster than defining your own container from scratch.

# Usage

Each image is built from a repo in the organisation which is published as a package within the organisation. To use this, you can use the image identifier in the table below by setting the `image` property of the `devcontainer` file to that value, e.g.

```
{
    "image":"ghcr.io/atomic-learning/codespace_docker_python_base"
}
```

# Images

The table below shows the current colelction of images, including the repo they are based on, the url of package, the identifier to be used in `devcontainer` files, and a short description.

| Repo | Package URL | Image Identifier | Description |
| --- | --- | --- | --- |
| [Link](https://github.com/Atomic-Learning/codespace_docker_python_base) | [Link](https://github.com/Atomic-Learning/codespace_docker_python_base/pkgs/container/codespace_docker_python_base) | ghcr.io/atomic-learning/codespace_docker_python_base | Base Python image for Codespaces content pages. Contains the latest version of Python and the packages:<br>- Numpy<br>- Scipy<br>- Matplotlib<br>- Pandas<br>- Ipykernel |


