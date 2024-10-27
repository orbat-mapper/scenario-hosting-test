# ORBAT Mapper scenario hosting test

The purpose of [this repository](https://github.com/orbat-mapper/scenario-hosting-test) is to show how to host scenarios for use with [https://orbat-mapper.app](https://orbat-mapper.app). ORBAT Mapper does not 
store scenarios on a server, but you can import scenarios from URLs and create a sharable link: 

![image](https://github.com/user-attachments/assets/03e44248-e2df-4ee7-9eed-1ae5b0896311)

Example of sharable URL for a scenario stored in this repo: [https://orbat-mapper.app/?loadScenarioURL=https%3A%2F%2Forbat-mapper.github.io%2Fscenario-hosting-test%2FFramland-Arnland-example.json](https://orbat-mapper.app/?loadScenarioURL=https%3A%2F%2Forbat-mapper.github.io%2Fscenario-hosting-test%2FFramland-Arnland-example.json)

A convenient place to store and host a scenario is [GitHub](https://github.com). For this to work you have to follow the following steps:

1. [Create a public repository and initialize it with a README]([https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository))
2. [Add your downloaded scenario files to the root of the repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository#adding-a-file-to-a-repository-on-github)

![image](https://github.com/user-attachments/assets/63fb34d1-8fe3-46d9-a2c1-79da969dc2a0)

3. [Create a Github Pages site from your repository](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site)
4. You now need to find the URL for the scenario JSON files you have uploaded. For this repository the `Framland-Arnland-example.json` files is hosted on the url [https://orbat-mapper.github.io/scenario-hosting-test/Framland-Arnland-example.json](https://orbat-mapper.github.io/scenario-hosting-test/Framland-Arnland-example.json) A convenient way to do this is to add links to them in the README.md file like this:
```markdowm
List of scenarios:
- [Framland-Arnland-example.json](Framland-Arnland-example.json)
```

List of scenarios:
- [Framland-Arnland-example.json](Framland-Arnland-example.json)
- [Scenario merge testing1.json](Scenario merge testing1.json)

When the site is published the README will be rendered with links that you can copy and paste into ORBAT Mapper. 
