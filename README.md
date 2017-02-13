# Assignment-1.4


Q1. Describe the characteristics of Big data in detail :

Characteristics Of 'Big Data' (i)Volume – The name 'Big Data' itself is related to a size which is enormous. Size of data plays very crucial role in determining value out of data. Also, whether a particular data can actually be considered as a Big Data or not, is dependent upon volume of data. Hence, 'Volume' is one characteristic which needs to be considered while dealing with 'Big Data'.

(ii)Variety – The next aspect of 'Big Data' is its variety.

Variety refers to heterogeneous sources and the nature of data, both structured and unstructured. During earlier days, spreadsheets and databases were the only sources of data considered by most of the applications. Now days, data in the form of emails, photos, videos, monitoring devices, PDFs, audio, etc. is also being considered in the analysis applications. This variety of unstructured data poses certain issues for storage, mining and analysing data.

(iii)Velocity – The term 'velocity' refers to the speed of generation of data. How fast the data is generated and processed to meet the demands, determines real potential in the data.

Big Data Velocity deals with the speed at which data flows in from sources like business processes, application logs, networks and social media sites, sensors, mobile devices, etc. The flow of data is massive and continuous.

(iv)Variability – This refers to the inconsistency which can be shown by the data at times, thus hampering the process of being able to handle and manage the data effectively.

(v)Value - Although Value is frequently shown as the fourth leg of the Big Data stool, Value does not differentiate Big Data from not so big data. It is equally true of both big and little data that if we are making the effort to store and analyze it then it must be perceived to have value.

Q2.Possible solutions to handle Big data :

Scale up:

· Increase the configuration of a single system,like capacity,RAM,Data transfer speed,etc.

· Complex,costly,and a time consuming process.

Scale out:

· Use multiple commodity machines and distribute the load of storage/processing among them.

· Economical and quick to implement as it focuses on distribution of load.

· Instead of having a single system with of 10TB of storage and 80GB of RAM,use 40 Machines with 256GB of Storage and 2GB of RAM.

Q3. Explain the differences between scaling up and scaling out.

(1).Scale-up : It refers to the process of adding more physical resources such as memory, storage and CPU to the existing database server for improving the performance. Vertical scaling helps in upgrading the capacity of the existing database server. It results in a robust system. Some of its pros include:

Pros of Scaling-Up

It consumes less power as compared to running multiple servers Administrative efforts will be reduced as you need to handle and manage just one system Cooling costs are lesser than horizontal scaling Reduced software costs Implementation isn’t difficult The licensing costs are less The application compatibility is retained

Cons of Scaling up

There is a greater risk of hardware failure which can cause bigger outages Limited scope of upgradeability in the future Severe vendor lock-in The overall cost of implementing is really expensive

(2).Scale-Out or Horizontal Scaling When you add more servers with less RAM and processors, it is known as horizontal scaling. It can also be defined as the ability to increase the capacity by connecting multiple software or hardware entities in such a manner that they function as a single logical unit. It is cheaper as a whole and it can literally scale infinitely, however, there are some limits imposed by software or other attributes of an environment’s infrastructure. When the servers are clustered, the original server is scaled out horizontally. If a cluster requires more resources to improve its performance and provide high availability, then the administrator can scale-out by adding more servers to the cluster.

Pros of Scaling-out

Much cheaper compared to scaling-up Takes advantage of smaller systems Easy to upgrade Resilience is improved due to the presence of discrete, multiple systems Easier to run fault-tolerance Supporting linear increases in capacity

Cons of Scaling-out

The licensing fees are more Utility costs such as cooling and electricity are high It has a bigger footprint in the Data Center More networking equipment such as routers and switches may be needed

