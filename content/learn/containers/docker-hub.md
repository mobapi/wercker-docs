## Docker Hub

Wercker currently supports containers obtained from [Docker
Hub](https://hub.docker.com), a marketplace for various Docker containers,
ranging from language stacks to databases.

![image](/images/dockerhub.png)

### Getting containers from Docker Hub

In order to use these containers you have to specify them in your
[wercker.yml](/learn/wercker-yml/introduction.html). You at least
need to specify  the main language stack you want to use via the `box`
section.

In the next section we'll explain how you can use containers in your
pipelines.

- - -
> Want to push containers to the Docker Hub? Read more on our
> [docs](/docs/containers/pushing-containers.html)

[&lsaquo; Introduction to containers](/learn/containers/introduction.html "nav previous containers")
[Using containers &rsaquo;](/learn/containers/using-containers.html "nav next containers")
