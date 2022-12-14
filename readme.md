![](https://img.shields.io/badge/status-Development-yellowgreen)
![GitHub tag (latest by date)](https://img.shields.io/github/v/release/marcos-paulo/ssh_tunneling)

<h1 align="center">SSH Tunneling</h1>

## Description

<p align="justify">This script creates an ssh tunnel on a specific port, with a server outside your local network, causing accesses made to the server on the internet to be redirected inside your local network without the need to create any firewall rules.</p>

## Requirements

<p align="justify">Set env file variables:</p>

- Copy the env_example file renaming it to env
- Set the values of the variables present in the env file

## Usage

<p align="justify">Go to the project directory</p>

```bash
$ cd ssh_tunneling
```

<p align="justify">Give execute permission to all files with the .sh extension</p>

```bash
$ chmod +x ./*.sh
```

Run the `main.sh` script

```bash
$ ./main.sh
```

## Deploy

If you use a `git push` mechanism to deploy to a server, connected via ssh authentication with an SSH key, you can use the deploy.sh script that to makes the job easier. [see more](./deploy/readme.md)
