# Introduction

The Atomic-Learning organisation includes a variety of images which are designed to be used in Codespaces supporting a content page. Using an image will typically speed up the time it takes to set up a Codespace as the image will already contain the necessary tools and packages for the content page, so they won't need to be installed each time a Codespace is created. It also reduces the amount of configuration needed in the `devcontainer` file as the image will already contain the necessary tools and packages, so they won't need to be specified in the `devcontainer` file.

# Usage

Each image is built from a repository in the Atomic-Learning organisation which is published as a package within the organisation. To use this, you can use the image identifier in the table below by setting the `image` property of the `devcontainer` file to that value, e.g.

```
{
    "image":"ghcr.io/atomic-learning/image-python-3-14-minimal"
}
```

# Images

The table below shows the current collection of images, including the repository they are based on, the URL of the package, the identifier to be used in `devcontainer` files, and a short description.

| Repo | Package URL | Image Identifier | Description |
| --- | --- | --- | --- |
| [Link](https://github.com/Atomic-Learning/image-python-3-14-minimal) | [Link](https://github.com/Atomic-Learning/image-python-3-14-minimal/pkgs/container/image-python-3-14-minimal) |  ghcr.io/atomic-learning/image-python-3-14-minimal | Minimal Python image supporting Jupyter Notebooks, but no other packages |
| [Link](https://github.com/Atomic-Learning/image-python-3-14-basic) | [Link](https://github.com/Atomic-Learning/image-python-3-14-basic/pkgs/container/image-python-3-14-basic) |  ghcr.io/atomic-learning/image-python-3-14-basic | Basic Python image containing the packages:<br>- Numpy<br>- Scipy<br>- Matplotlib<br>- Pandas<br>- Ipykernel |