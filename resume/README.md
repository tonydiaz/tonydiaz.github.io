# Steps to setup a run JSONResume
I'm using JSONresume to generate the resume webpage.

### Install the JSONResume [resume-cli](https://github.com/jsonresume/resume-cli) project first:

```
npm install -g resume-cli
```
## Test the JSON schema to ensure it is valid:
```
resume test resume.json
```

### Export the resume.json file to HTML or PDF including the theme you want:

```
resume export resume.json -f .html -t elegant
resume export resume.json -f .pdf -t paper
```
