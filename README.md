# Become a Game Distribution Company in 3 Commands!

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
Optional hardware:
raspberry pi
6 TB HDD
SATA Adapter

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

Create a VPS account

list of Providers that offer Unmettered Traffic:
https://ungleich.ch/
https://zetservers.com/
https://www.vps9.net/
https://www.fastpipe.io/
https://servercheap.net/
https://www.primahost-ng.com/
https://www.enoctus.co.uk/
https://www.zelon.com/
https://afterburst.com/
https://www.ovh.com/
https://buyvm.net/
https://contabo.com/

I can vouch for OVH. For $3.50 you can get syymetrical 100Mbit/s traffic. Perfect for non gigabit home internet.

Create a Ubuntu 18.04 VM

Run Wireguard Ansible playbook to setup VPN Server.

Connect client to VPN.

Use the mirror option to recursivly download a whole site. Not Google of course!...though I havent tried.

wget --mirror fitgirl-repacks.site

I have included a mirror of the site in my repo. I suggest you use mine as to not take their site offline.

Grep command with search pattern to extract magnet link hash.This hash can be imported into clients such as qBittorent.

grep -RisIowh -m 1 "[[:xdigit:]]\{40\}" * | sort --unique > master.txt

-m 1 stops after first match becasue sometimes two links for one file are on a page

this will leave you with a very large list of hashes.

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Ansible](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [wget](https://maven.apache.org/) - Dependency Management
* [grep](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Leo** - *Initial work* - [here](https://github.com/)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

Public Domain

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
