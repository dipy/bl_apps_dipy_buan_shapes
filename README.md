# Dipy Workflow Wrapper

This is a Brainlife wrapper App for `dipy_buan_shapes` workflow. This single wrapper is exposed through an apps registered on [Brainlife.io](https://brainlife.io).

- More information about DIPY : [https://dipy.org/](https://dipy.org/)
- More information about the command line `dipy_buan_shapes`: [Command line Reference](https://dipy.org/documentation/1.2.0./interfaces/buan_flow/)

## Running the App

#### 1. On Brainlife.io

You can see a list of [Dipy Apps currently regsitered on Brainlife](https://brainlife.io/apps#dipy). Find the App that you'd like to run and click "Execute" tab to specify dataset that you'd like to run the App on.

#### 2. On  your machine (Running Locally)

To run this command, you can simply type:

`singularity exec -e docker://brainlife/dipy:1.1.1 dipy_buan_shapes [your_args]`

To see the documentation of all arguments, [go to the following page](https://dipy.org/documentation/1.2.0./interfaces/buan_flow/)

### Dependencies

This app runs on [singularity](https://www.sylabs.io/singularity/).
