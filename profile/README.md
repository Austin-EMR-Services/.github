# Austin Health EMR Services Projects

### Guidelines:

#### Modifcation to existing build
If you are modifying an existing build, search for that build in **Repositories** and submit all changes via a pull request to that repository.

#### New build
If you are creating new build, or you are modyfing existing build that does not have a repository, *Create a new* repository.
  - Your new repository should be prefixed with some letters indicating the primary build type (e.g. 'ST' from smart template, 'CC' for custom component, 'DR' for discern rule, and 'EMRC' for EMR content.
  - Create your repository as a *Private* repository.
  - Add a README file.
  - Create the repository.
  - Edit the README file to follow the following format
  
      ># Title of the repository
      >
      >**Jira Reference Number:** The jira ticket number (e.g. EMRCR-100)
      >
      >**Build Type:** The coding languages used in the build (e.g. ccl, js, html, etc.)
      >
      >**Where Used:** A brief one-line description of the architecture of the build (e.g. ccl program called by public autotext phrase)
      >
      >**Purpose:** A brief one-line description of the purpose of the build for some context
      >
      >**Dependencies:** Any third-party libraries/plugins used by the build

  - Navigate to the repository homepage and use the cog in the top right corner to add a URL to the Jira ticket (if one exists) for this build.
  - In the same modal, add relevant high-level tags about the build to help with identification (e.g. the programming language used, the architecture of the build).
