# liquibase-drift-reports
## A quick python setup for automating diff reports (aka drift reports) using the new Liquibase Pro diff as json capability


## Purpose & Goal
RoboFlow was created to get a better sense for TensorFlow's image classifier by making it easier to gather 1000s of similar images by hashtag (such as "#robot" or "#robotart") to serve as re/training examples, and to enable easy testing of different TensorFlow hyperparameter settings for creating classifiers. specifically, tagged images are downloaded (your choice of Imgur API or from web.stagram.com) and then sorted into labeled sub-directories, according to a 'confidencemin' variable, which are periodically 'harvested' to retrain TensorFlow to create new classifiers.<br>
<b>Issues, Contributions, and Pull Requests welcomed!</b>




## Getting Started
These instructions will get you a copy of the roboflow project up and running on your local machine for development and testing purposes.


### Prerequisites

#### software
* Liquibase (<a href="https://liquibase.com/">https://liquibase.com/</a>) 
* Python3 (<a href="https://www.python.org/downloads/">https://www.python.org/downloads/</a>)
* Terminal/Command Line familiarity


#### permissions
* Internet Access
* File and directory creation permissions
* Optional: Create aliases in ~/.bash_profile (or equivalent)


## Installing

```
git clone https://github.com/mariochampion/roboflow
```


Your directories should look like this:
```
├── tensorflow
|  ├── roboflow
|  ├── scripts
|  ├── tf_files
|  |  ├── bottlenecks
|  |  ├── models
|  |  ├── testing_photos
|  |  |  ├── [autogenerated basetag dirs...]
|  |  ├── training_photos
|  |  |  ├── [autogenerated basetag dirs...]
|  |  ├── training_summaries
|  |  |  ├── [autogenerated basetag dirs...]
```


Et voila, you are ready to explore!

## Guided usage:
```
python drift_reports.py
```
#### As a shortcut, add an alias in your .bash_profile to launch it via alias 'drift_report':
```
nano ~/.bash_profile
alias roboflow="cd path/to/install/dir/;python drift_report.py"
```


## Contributing

I am very open to issues and pull requests. Looking for a place to start helping?<br>
https://github.com/mariochampion/liquibase-drift-reports

## Authors

* **Mario Champion** - *Initial work* - [mariochampion](https://github.com/mariochampion)

Contributions, Issues, and Pull requests Welcome!

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Liquibase Community
* StackExchange
* Python

## thanks and always remember: this robot loves you. 
## boop boop!