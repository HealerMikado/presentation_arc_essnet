Hello everyone, I'm Remi Pépin and I will present the aquisition, reception, control, or ARC aplication.

Fun fact, ARC means bow in French, and at Insee ARC is used by an application named Artemis, which is the greek godness of the Hunt, and use bow.

OK what is the pruspose of arc ? ARC is the entry point of administrative data in a informational system. It can receive, control and transform data in stable and statical one. And it can take change in input data easily.

Here is the arc worklow at Insee. First we register the data to process, then we identify what is theirs type, and how we haev to load their. After that the files are loaded in databse. This 3 steps avec mandatory. After that we have a phase of structuration of the file, then one which control its integrity, after that we can filter some lines, and finaly we create the ouput file with a stable and statistical friendly model.

The main features of arc are :

all the rules by the application are defined by the users. There totaly autonomous !
The app is optimized with multi threading and database parralelisation
and there are build in sand box for the rules developpement

The arc application is made up of different services, each one have one purpose. Some are mandatory, other can be disable, and the order between services can be changed.

As you can see, ARC cover a lot of the process modul of the GSBPM. And with the build in sandbox you can design and test process.

The arc application is a commun 3 tiers application with a Tomcat server and a postgres SQL database. We are currently working on the conternerisation of the application with docker. And make is installation easier.

