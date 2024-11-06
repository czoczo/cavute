# CasaVue demo
https://awesome-selfhosted.casavue.app

## Repo content
This repo is a simple example of how [CasaVue](https://casavue.app) can be used to generate a static home page based on [GitHub Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) list of applications containing demo link.

```
.
├── .github
│   └── workflows
│       └── build-page.yaml    # Web page build and publish script
├── config                          # CasaVue config files
│   └── main.yaml
├── items_config_generator.py       # Script for scraping data from GitHub Selfhosted repo
├── README.md
└── requirements.txt                # Set of dependencies for python script
```

All steps are implemented in [Github Workflow](https://github.com/czoczo/casavue-awesome-selfhosted/blob/main/.github/workflows/build-demo-page.yaml).  
Description of configuration files may be found [here](https://casavue.app/configuration/file/).
