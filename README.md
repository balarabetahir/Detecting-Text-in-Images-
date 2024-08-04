# Stroke Width Transform


## Example

To run SWT with connected components against the `15_02.jpg` example image, execute

```bash
python main.py img/15_02.jpg
```

Given the following image ...

![](img/15_02.jpg)

... it will find these connected components:

![](.readme/connected-components.png)

## Conda environment

A conda environment is available in `environment.yaml`. To create and activate it, run

```bash
conda env create -f environment.yaml
conda activate swt
```