# Nginx Tutorial - Session 02: Basic Architecture and Installing Nginx

Welcome to Session 02 of the Nginx Tutorial, where we'll explore the basic architecture of Nginx and learn how to install it on Ubuntu and CentOS.

## Table of Contents

1. [Nginx Process](#nginx-process)
   - [Master and Worker](#master-and-worker)
     - [Count of Workers](#count-of-workers)
     - [Connection Handling](#connection-handling)
2. [Nginx Commands](#nginx-commands)
   - [Basic Commands](#basic-commands)
   - [Useful Switches](#useful-switches)
     - [-h](#-h)
     - [-v](#-v)
     - [-V](#-V)
     - [-t](#-t)
     - [-T](#-T)
     - [-s](#-s)
   - [Additional Commands](#additional-commands)
     - [reload](#reload)
     - [stop](#stop)
     - [quit](#quit)
     - [reopen](#reopen)
3. [Directories](#directories)
   - [/var/www/html](#/var/www/html)
   - [/etc/nginx](#/etc/nginx)
   - [/etc/nginx/nginx.conf](#/etc/nginx/nginx.conf)
   - [/etc/nginx/sites-available/](#/etc/nginx/sites-available/)
   - [/etc/nginx/sites-enabled/](#/etc/nginx/sites-enabled/)
   - [/etc/nginx/conf.d/](#/etc/nginx/conf.d/)
   - [/etc/nginx/stream.conf.d/](#/etc/nginx/stream.conf.d/)
   - [/etc/nginx/snippets/](#/etc/nginx/snippets/)
   - [/var/log/nginx/access.log and error.log](#/var/log/nginx/access.log-and-error.log)
   - [/etc/ssl/certs](#/etc/ssl/certs)
4. [Nginx Config Files](#nginx-config-files)
   - [Blocks](#blocks)
   - [End with ;](#end-with-;)
5. [Preparation Before Installing](#preparation-before-installing)
   - [Update and Upgrade](#update-and-upgrade)
   - [Time Zone and Time](#time-zone-and-time)
   - [Firewall](#firewall)
6. [Installing Nginx](#installing-nginx)
   - [On Ubuntu](#on-ubuntu)
   - [On CentOS](#on-centos)

## Nginx Process

### Master and Worker

Nginx operates with a master process that manages multiple worker processes. These workers handle incoming connections.

#### Count of Workers

The number of worker processes can be configured according to your server's resources.

#### Connection Handling

Nginx effectively handles client connections, serving web content, and other tasks.

## Nginx Commands

### Basic Commands

Nginx provides several basic commands to control its operation.

### Useful Switches

Nginx commands can be augmented with switches for specific functionality.

#### -h

Get Nginx help.

#### -v

Get Nginx version.

#### -V

Get Nginx version and compile options.

#### -t

Test Nginx configuration.

#### -T

Test Nginx configuration and dump it to the standard output.

#### -s

Signal Nginx processes.

### Additional Commands

Nginx also supports other commands for various purposes.

#### reload

Reload the configuration file without stopping Nginx.

#### stop

Stop Nginx processes fast.

#### quit

Perform a graceful shutdown of Nginx processes.

#### reopen

Reopen log files without restarting Nginx.

## Directories

Nginx uses various directories and files for its configuration and operation.

- `/var/www/html`: The default web content directory.
- `/etc/nginx`: Nginx configuration files.
- `/etc/nginx/nginx.conf`: Main Nginx configuration file.
- `/etc/nginx/sites-available/` and `/etc/nginx/sites-enabled/`: Configuration for sites.
- `/etc/nginx/conf.d/` and `/etc/nginx/stream.conf.d/`: Additional configurations.
- `/etc/nginx/snippets/`: Reusable configuration snippets.
- `/var/log/nginx/access.log` and `/var/log/nginx/error.log`: Nginx log files.
- `/etc/ssl/certs`: SSL certificate storage.

## Nginx Config Files

Nginx configuration files consist of various blocks, each serving a different purpose.

- Blocks: `server`, `http`, `stream`, `location`, and more.
- Configuration statements end with a semicolon (;).

## Preparation Before Installing

Before installing Nginx, it's essential to prepare your server environment.

- Update and upgrade your system.
- Set your server's time zone and time settings.
- Adjust firewall rules for Nginx operation.

## Installing Nginx

### On Ubuntu
sudo apt-get install nginx

### On CentOS
sudo yum install nginx
