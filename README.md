
Check 5 partitions and 10 raid
==============
## Descriptions
This vagrant creates a vm, installs the necessary packages to complete the job, builds 10 raids, creates a gpt partition and 5 partitions. 

## Setup and run
* **Step 1**: Using Command Terminal, download and install: ```git clone https://github.com/rxsd20/gpt-5-partitions.git```

* **Step 2**: Go to the directory with command: ```cd gpt-5-partitions```

* **Step 3**: Run the command: ```vagrant up```

* **Step 4**: Go in VM command: ```vagrant ssh```

* **Step 5**: Enter command: ```lsblk```

* **Step 6**: Exit VM: ```exit```


## Vagrant Commands
* **Start VM**: ```vagrant up```
* **Hibernate VM**: ```vagrant suspend```
* **Restart VM**: ```vagrant reload```
* **Destroy VM**: ```vagrant destroy```
* **Remove from Vagrant Box List**: ```vagrant box remove rxsd20/centos-7-5```

#### SSH Info
* User: vagrant
* Password: vagrant
