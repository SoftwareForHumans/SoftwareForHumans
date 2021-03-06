# Software for Humans

_Software for Humans_ aggregates Software Engineering researchers exploring and studying how to improve the lives of software developers, through new approaches and tools that support everyday software development activities. Watch this repository, as we will soon add more information about our works and results. For now, you can learn below about two of our most promising tool prototypes: _Dockerlive_ and _Hermit_.

## Dockerlive

[DockerLive](https://github.com/davidreis97/Dockerlive) is an open-source plugin for VSCode that uses live programming to increase the amount of feedback received by a developer when developing Dockerfiles. We have already shown this approach to be very useful for developers, but much more can be done to extend and refine DockerLive's current feature set. Additional features could include using intellisense to suggest specific ports in a `EXPOSE` instruction, or to suggest typical instructions for specific environments (*e.g.*, `RUN npm install`), or automatically suggest fixes for broken Dockerfiles, possibly by tracing the runtime behaviour of the processes within the resulting container.

<details>
  <summary>Show Dockerlive example (GIF)</summary>
  
![Dockerlive example.](/media/dockerlive_example.gif)
</details>

## Hermit

[Hermit](https://github.com/Raidenkyu/hermit) is an open-source command line tool to automatically generate Dockerfiles for any arbitrary project. Hermit works by analysing the code repository of a project, determining its dependencies and ports, and generating a fully working Dockerfile for that project. We have shown Hermit to work well for a variety of projects, and evaluated it against a large set of randomly-selected projects hosted in GitHub. We would now like to extend Hermit to support a wider range of projects, and to improve the generation of Dockerfiles to result in more optimized containers (_e.g._, with special focus on their size, security, etc.).
