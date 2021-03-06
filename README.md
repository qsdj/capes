# Cyber Analytics Platform and Examination System (CAPES)
![capes logo](http://capesstack.io/capes_logo.png)

**People ask from time-to-time what help is needed - documentation. If you see documentation that is wrong, be it grammar, incorrect guidance, or missing; please consider doing a PR correcting it. I will gladly give contributor status to anyone who does anything to make this project easier for people to get started.**

CAPES is an operational-focused service hub for segmented, self-hosted, and offline (if necessary) incident response, intelligence analysis, and hunt operations.

![capes architecture](http://capesstack.io/capes_arch.png)

## Services in CAPES
1. Rocketchat (Chat)
1. Etherpad (Collaboration-style documentation)
1. Gitea (Version controlled documentation)
1. CyberChef (Data analysis)
1. Mumble (VoIP)
1. TheHive (Incident Response)
1. Cortex (Indicator enrichment)
1. Kibana (Data visualization)
1. Beats - Metric, Heart, and File (Performance and health metrics)

## Roadmap
1. Get working shell script for all services
1. Get shell scripts combined into a singular CAPES deploy script
1. Documentation *
1. Convert CAPES to Docker

## Note
\* designates current effort

## Documentation / Installation
See [docs](docs/README.md) for detailed instructions.  

### CentOS 7.4
```
$ sudo yum -y install git
$ git clone https://github.com/capesstack/capes.git
$ cd capes
$ sudo sh deploy_capes.sh
```
### Pre-CentOS 7.4
```
$ sudo yum install -y https://kojipkgs.fedoraproject.org/packages/http-parser/2.7.1/3.el7/x86_64/http-parser-2.7.1-3.el7.x86_64.rpm
$ sudo yum -y install git
$ git clone https://github.com/capesstack/capes.git
$ cd capes
$ sudo sh deploy_capes.sh
```
## Usage
1. See the [Build, Operate, Maintain guides](docs/README.md) to complete post-installation configuration
1. Browse to http://capes_IP

# Troubleshooting
Please see the [documentation](https://github.com/capesstack/capes/tree/master/docs#documentation) or feel free to open a [GitHub Issue](https://github.com/capesstack/capes/issues).

Want to join the discussion? Send a request to join our Slack Workspace to contact [at] capesstack[.]io

# Training & Professional Services
While CAPES is a FOSS project and we'll attempt to support deployment questions via the Issues page, if you need training or PS, please feel free to check out some options over at [Perched](http://perched.io)
