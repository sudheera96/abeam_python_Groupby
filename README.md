# abeam_python_Groupby

## What is apache beam?

Apache Beam basically a data processing platform. Data processing can be either for analytics purpose or it can be ETL (Extract, Transfer, Load). Apache beam  doesn't
reply on any one execution engine.The input data can be streaming data or batch data. Input data can be from some database like relational database or memory database. so
apache beam is execution platform agnostic and data agnostic also programming agnostic i.e, it supports multiple programming language you can write your logic in java python,go.

![](https://www.slideteam.net/media/catalog/product/cache/960x720/d/a/data_flow_model_and_sdks_pipelines_slide01.jpg)

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











































