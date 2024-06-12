# LLM CLI Cheatsheet

This repository contains a file that provides some useful helper functions that invoke the `llm` cli from Simon Willisons [llm-cli](https://github.com/simonw/llm).

`llm` is a very usefull cli tool that works with a various set of llm models.

Currently it always calls and uses the default model that is configured for `llm` 


## Usage

1. install `llm` from Simon Willison, install introductions can be found [here](https://llm.datasette.io/en/latest/setup.html)
2. configure the default model you would like to use with `llm models default <modelid>`
3. clone this repository and source the `llm-cli-cheatsheet` with the following command `source llm-cli-cheatsheet`

The file itself contain some documentation how to use the cheatsheet

## Functions

The following functions are currently provided


| Function               | Description                                                      | Example |
|------------------------|------------------------------------------------------------------|---------|
| `llm.git.msg`       | Generates a Git commit message from the git diff output | `llm.git.msg` |
| `llm.git.compare`       | Compares two revisions of the current git repository | `llm.git.compare main dev` |
| `llm.code.testdata`  | Creates test data for a given file  | `llm.code.testdata user.ts` |
| `llm.code.explain`   | Provides explanations for the code within a specific file | `llm.code.explain user.ts` |

## Contribution

If you have usefull functions you would like to add, please do not hesitate to file a pull request. We love to see this cheatsheet grow!
