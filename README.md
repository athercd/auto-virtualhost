# <p align="center">Auto Virtual Host Apache</p>
Hey when we are work in new project then its annoying to create new virtual hosts checking all those boring things if not work then fixing bug on hosts file etc.... So There is a script to create your virtual host automatically. Just run script and BooooooooooooM! Host created within a second.
```
Create Screenshot
```
![screenshot_nym_2020-09-09_2](https://user-images.githubusercontent.com/40033062/92630467-bbcc7400-f2f1-11ea-9361-8be867e4e299.png)
```
Delete Screenshot
```
![screenshot_nym_2020-09-09_3](https://user-images.githubusercontent.com/40033062/92630420-a8b9a400-f2f1-11ea-9c57-e49685c09c99.png)
```
List Screenshot
```
![screenshot_nym_2020-09-10](https://user-images.githubusercontent.com/40033062/92641126-1967bd00-f300-11ea-8290-ef702355e42b.png)

## Features
* Create New Virtualhost
* Delete an Existing Host
* View all List of Existing Host
* Compatible with nginx and apache <b>[Upcoming...]</b>

## Process of Installation

1. Clone or download this repo

```
git clone https://github.com/nayeemdev/auto-virtualhost-apache
```
```
cd auto-virtualhost-apache
```
2. Give permission for executing:

```
chmod +x virtualhost.sh
```

## How To Use

```
sudo ./virtualhost.sh [create/delete] [domain_name] [your_project_full_directory_path]
```

## Using Examples

```
sudo ./virtualhost.sh create nayeem.test /var/www/html/nayeem
```

## Run Host
###### GoTo Your Browser and run http://your_domain


# <p align="center">*****Extra Tips*****</p>
<p align="center">Hey here is a tips for you.</p>
<p align="center">You can run this script globally if you want just follow up these steps</p>

## Globally Use
Run this Command for copy sh file to local bin directory
```
sudo cp virtualhost.sh /usr/bin/virtualhost
sudo cp virtualhost.sh /usr/local/bin
```
For create virtual host
```
 sudo virtualhost [create/delete] [domain_name] [your_project_full_directory_path]
```


## Global Example

```
sudo virtualhost create nayeem.test /var/www/html/nayeem
```


## Want to contribute?
<p>Clone this repo add/change what you want and send a pull request. ##Happy Coding##</p>
