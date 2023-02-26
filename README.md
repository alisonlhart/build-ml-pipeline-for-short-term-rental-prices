# Build an ML Pipeline for Short-Term Rental Prices in NYC

From the Udacity Course: Machine Learning Devops Engineer

This project is a pipeline that builds a random forest model and trains it on the NYC rental dataset. You can use other datasets as needed for retraining. The syntax to do so is in the deployment instructions below. 

## Weights And Biases Project Link

https://wandb.ai/allhart/nyc_airbnb

## Github Link

https://github.com/alisonlhart/build-ml-pipeline-for-short-term-rental-prices

## Release Notes

### v1.0.1

Resolved a test error related to longitude and latitude boundaries.

### v1.0.0

Initial pipeline release.

## Deployment Instructions

### Cloning repository for local run

Clone the repository locally. 
Navigate to the root of the local repository.

Use `mlflow run .` to run all steps.

### Calling repository from Github URL

Use `mlflow run <HTTPS GITHUB URL.git> -v <VERSION TAG> -P hydra_options="elt.sample='<DATA>'"`

## Environment Dependencies (environment.yml)
```
dependencies:
  - python=3.8.16
  - mlflow=1.14.1
  - ipython=7.21.0
  - notebook=6.2.0
  - jupyter=1.0.0
  - jupyterlab=3.0.12
  - cookiecutter=1.7.2
  - hydra-core=1.0.6
  - matplotlib=3.3.4
  - pandas=1.2.3
  - git=2.30.2
  - pip=20.3.3
  - pip:
      - wandb==0.10.31
      - numpy==1.20.0
      - protobuf==3.20.1
```

## License

[License](LICENSE.txt)
