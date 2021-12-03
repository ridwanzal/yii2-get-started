#### Author : M. Ridwan Zalbina

# Getting started with yii version 2

## Overview
Yii is a high performance, component-based PHP Framework for rapidly developing modern web applications. The name Yii (pronounced “Yee”) means “simple and evolutionary” in Chinese. Yii is an open source PHP framework based on the MVC model. It contains many libraries and functions which help you in creating your website easily. Yii2 is the latest version of Yii and it is the 4th most used PHP framework in 2015, still going strong in 2016.


## Reason to use Yii PHP Framework
- **Gii**
Yii 2 has a code generation tool called Gii. Gii analyzes your database tables and automatically builds PHP models from them. Not only that, but it analyzes the relationships between tables and automatically generates the relational code into the models. For example, if you had a data structure with 30 tables, and half of them had a user_id column that was meant to reference the id of the user table, Gii would build the appropriate relationships for you, all in one go. Not only is this a time-saver, but this also gives you very consistent code because it is always done the same way and it helps you adopt this discipline.
DB-first approach
Since Yii 2 allows you to essentially import the models from the data structure, you can start your project by really thinking through your data structure. Whether you are a single developer or part of an enterprise level team, you are essentially being given the same task, the same overall mission. You have to serve data from a database into a browser- friendly format, typically using PHP, HTML, and Javascript. We use a PHP framework to make this task easier, and by saying that, we are admitting upfront that it’s not an easy task
- **Minimum PHP Skills**
- **Beautiful and good documentation**


## Model-View-Controller Paradigm
Yii 2 follows the MVC design pattern. MVC is an application designing model which lets you create your app easily. M stands for Model which represents the application core and lets you connect with the database and perform all CRUD tasks, perform validations and much more. But it doesn’t contain any information about the design and view of applications. V stands for Views which contains the designs and views of your application. It pertains to how the data which comes from the Model will be shown to users. C stands for Controller, which helps you to connect your Model and View together. In other words, it is used to communicate between the Model and View class so that the data that is coming from the Model can easily be integrated on 
