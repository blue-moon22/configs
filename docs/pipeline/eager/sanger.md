# nf-core/configs: Sanger eager specific configuration

Extra specific configuration for the Sanger to run the [nf-core/eager pipeline](https://github.com/nf-core/eager)

## Usage

To use, run the pipeline with `-profile sanger`.

This will download and launch the eager specific [`sanger.config`](../../../conf/pipeline/eager/sanger.config) which has been pre-configured with a setup suitable for the LSF cluster.

Example: `nextflow run nf-core/eager -profile sanger`

## eager specific configurations for Sanger

Specific configurations for the Sanger has been made for eager with default [nf-core/eager](https://github.com/nf-core/eager) parameters.
