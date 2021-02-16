<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSFdAvw2XOHzl55u-rBk2XMdtGh14HiTzS1AA&usqp=CAU" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="40" height="60">
# abeam_python_Groupby

## What is apache beam?

Apache Beam basically a data processing platform. Data processing can be either for analytics purpose or it can be ETL (Extract, Transfer, Load). Apache beam  doesn't
reply on any one execution engine.The input data can be streaming data or batch data. Input data can be from some database like relational database or memory database. so
apache beam is execution platform agnostic and data agnostic also programming agnostic i.e, it supports multiple programming language you can write your logic in java python,go.
<p align="center">
<img src="https://www.slideteam.net/media/catalog/product/cache/960x720/d/a/data_flow_model_and_sdks_pipelines_slide01.jpg"
     alt="Size Limit logo by Anton Lovchikov" width="650" height="500">
 </p>

## Terminology 
* `Pipelines` 
End to end data processing.
* `Pcollection`
Reading of the input data is p collection applying any transormations on that data and creating new data from that is also p collection.
* `Ptransorm`
Logic applying to data is p transform ((https://beam.apache.org/documentation/programming-guide/#transforms)
* `PRunner`
specifies where and how the pipeline should execute.

![](https://miro.medium.com/max/4500/1*KSbxc89zsZ-AWLJSsAtPvQ.png)

## Quickstart

### Check versions
```powershell
python --version
```
```powershell
pip --version
```
python must be 3.6 or higher, pip must be 7.0.0 or newer

### Install apache beam
```powershell
python -m pip install apache-beam
```
- Extra Requirements

Installation for extra dependencies follow below command
```powershell
pip install apache-beam[gcp,aws,test,docs]
```
For more detail go to this [link](https://beam.apache.org/get-started/quickstart-py/)

## Google Colab

Google Colab has python preinstalled. On it, it is easy to start using apache beam.

* Open firefox or safari browser
* Type Google Colab
* Click on first link that is Google Colab
* Sign in with google account
* Click on notebook after appearing the window with recent

`Note: Google Colab works similar to jupyter notebook`

* After writing and execution of code,save file in local or Github

Look at my [netflixGroupBy.ipynb](https://github.com/sudheera96/abeam_python_Groupby/blob/main/netflixGroupBy.ipynb) Colab python notebook


## Resources

[Apache Beam Group By](https://beam.apache.org/documentation/transforms/python/aggregation/groupby/)

[Kaggle data set](https://www.kaggle.com/shivamb/netflix-shows)

[Apache Beam Colab](https://colab.research.google.com/github/apache/beam/blob/master/examples/notebooks/get-started/try-apache-beam-py.ipynb)









































