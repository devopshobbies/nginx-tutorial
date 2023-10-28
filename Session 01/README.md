# Nginx Tutorial - Session 01: What is Nginx?

Welcome to Session 01 of the Nginx Tutorial, where we'll explore the fundamentals of Nginx.

## Table of Contents

1. [Basics](#basics)
    - [Web Serving](#web-serving)
    - [Reverse Proxying](#reverse-proxying)
    - [Caching](#caching)
    - [Load Balancing](#load-balancing)
    - [Media Streaming](#media-streaming)
2. [Compare](#compare)
    - [IIS](#iis)
    - [Apache](#apache)
    - [Other Web Servers](#other-web-servers)
3. [Different Versions](#different-versions)
    - [nginx-core](#nginx-core)
    - [nginx-full](#nginx-full)
    - [nginx-light](#nginx-light)
    - [nginx-extras](#nginx-extras)
4. [License](#license)
    - [Nginx Open-Source](#nginx-open-source)
    - [Nginx Plus](#nginx-plus)
5. [Sources of this course](#sources-of-this-course)
    - [NGINX Cookbook Advanced Recipes](#nginx-cookbook-advanced-recipes)
    - [Official Nginx Website](#official-nginx-website)
    - [Online Search](#online-search)
    - [Personal Experience](#personal-experience)

## Basics

In this section, we'll cover the fundamental aspects of Nginx, including its various use cases:

- **Web Serving**: Nginx's primary role as a web server.
- **Reverse Proxying**: Using Nginx to act as a reverse proxy.
- **Caching**: How Nginx can be used for caching content.
- **Load Balancing**: Load balancing techniques with Nginx.
- **Media Streaming**: Nginx's capabilities in media streaming.

## Compare

Here, we'll compare Nginx with other web servers and see how it stands out:

- **IIS**: A comparison with Microsoft Internet Information Services.
- **Apache**: A comparison with the Apache HTTP Server.
- **Other Web Servers**: A brief look at how Nginx compares to other web servers.

## Different Versions

Nginx comes in various flavors, each designed for specific use cases:

- **nginx-core**: The core version of Nginx.
- **nginx-full**: The full-featured version.
- **nginx-light**: A lightweight version.
- **nginx-extras**: An extended version with additional features.

## License

Nginx is available under different licensing options:

- **Nginx Open-Source**: The open-source version of Nginx.
- **Nginx Plus**: The commercial version with additional features and support.

## Sources of this course

This course draws from various sources for a comprehensive understanding of Nginx:

- **NGINX Cookbook Advanced Recipes for High-Performance Load Balancing**: This cookbook provides advanced recipes for optimizing Nginx configurations.
- **[Official Nginx Website](https://nginx.org/en/)**: The official Nginx website is an excellent resource for documentation and updates.
- **Online Search**: Leveraging web resources for additional information.
- **Personal Experience**: Insights and knowledge gained through practical experience.

# Nginx different versions 
| Module               | nginx-core | nginx-full | nginx-light | nginx-extras |
|----------------------|------------|------------|-------------|-------------|
| **Core Modules**     |            |            |             |             |
| Core                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Access               | ✔️         | ✔️         | ✔️          | ✔️          |
| Auth Basic           | ✔️         | ✔️         | ✔️          | ✔️          |
| Auto Index           | ✔️         | ✔️         | ✔️          | ✔️          |
| Browser              | ✔️         | ✔️         |             | ✔️          |
| Empty GIF            | ✔️         | ✔️         | ✔️          | ✔️          |
| FastCGI              | ✔️         | ✔️         | ✔️          | ✔️          |
| Geo                  | ✔️         | ✔️         |             | ✔️          |
| Limit Connections    | ✔️         | ✔️         |             | ✔️          |
| Limit Requests       | ✔️         | ✔️         |             | ✔️          |
| Map                  | ✔️         | ✔️         | ✔️          | ✔️          |
| Memcached            | ✔️         | ✔️         |             | ✔️          |
| Proxy                | ✔️         | ✔️         | ✔️          | ✔️          |
| Referer              | ✔️         | ✔️         |             | ✔️          |
| Rewrite              | ✔️         | ✔️         | ✔️          | ✔️          |
| SCGI                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Split Clients        | ✔️         | ✔️         |             | ✔️          |
| UWSGI                | ✔️         | ✔️         | ✔️          | ✔️          |
| **Optional Modules** |            |            |             |             |
| Addition             | ✔️         | ✔️         |             | ✔️          |
| Auth Request         | ✔️         | ✔️         | ✔️          | ✔️          |
| Charset              | ✔️         | ✔️         | ✔️          | ✔️          |
| WebDAV               | ✔️         | ✔️         | ✔️          | ✔️          |
| FLV                  |            |            |             | ✔️          |
| GeoIP                | ✔️         | ✔️         |             | ✔️          |
| Gunzip               | ✔️         | ✔️         |             | ✔️          |
| Gzip                 | ✔️         | ✔️         | ✔️          | ✔️          |
| Gzip Precompression  | ✔️         | ✔️         | ✔️          | ✔️          |
| Headers              | ✔️         | ✔️         | ✔️          | ✔️          |
| HTTP/2               | ✔️         | ✔️         | ✔️          | ✔️          |
| Image Filter         | ✔️         | ✔️         |             | ✔️          |
| Index                | ✔️         | ✔️         | ✔️          | ✔️          |
| Log                  | ✔️         | ✔️         | ✔️          | ✔️          |
| MP4                  |            |            |             | ✔️          |
| Embedded Perl        |            |            |             | ✔️          |
| Random Index         |            |            |             | ✔️          |
| Real IP              | ✔️         | ✔️         | ✔️          | ✔️          |
| Slice                | ✔️         | ✔️         | ✔️          | ✔️          |
| Secure Link          |            |            |             | ✔️          |
| SSI                  | ✔️         | ✔️         | ✔️          | ✔️          |
| SSL                  | ✔️         | ✔️         | ✔️          | ✔️          |
| SSL Preread          | ✔️         | ✔️         |             | ✔️          |
| Stub Status          | ✔️         | ✔️         | ✔️          | ✔️          |
| Substitution         | ✔️         | ✔️         |             | ✔️          |
| Thread Pool          | ✔️         | ✔️         | ✔️          | ✔️          |
| Upstream             | ✔️         | ✔️         | ✔️          | ✔️          |
| User ID              | ✔️         | ✔️         |             | ✔️          |
| XSLT                 | ✔️         | ✔️         |             | ✔️          |
| **Mail Modules**     |            |            |             |             |
| Mail Core            | ✔️         | ✔️         |             | ✔️          |
| Auth HTTP            | ✔️         | ✔️         |             | ✔️          |
| Proxy                | ✔️         | ✔️         |             | ✔️          |
| SSL                  | ✔️         | ✔️         |             | ✔️          |
| IMAP                 | ✔️         | ✔️         |             | ✔️          |
| POP3                 | ✔️         | ✔️         |             | ✔️          |
| SMTP                 | ✔️         | ✔️         |             | ✔️          |
| **Stream Modules**   |            |            |             |             |
| Stream Core          | ✔️         | ✔️         |             | ✔️          |
| GeoIP                | ✔️         | ✔️         |             | ✔️          |
| GeoIP2               |            | ✔️         |             | ✔️          |
| **Third-party Modules** |         |            |             |             |
| Auth PAM             |            | ✔️         |             | ✔️          |
| Cache Purge          |            |            |             | ✔️          |
| DAV Ext              |            | ✔️         |             | ✔️          |
| Echo                 |            | ✔️         | ✔️          | ✔️          |
| Fancy Index          |            |            |             | ✔️          |
| GeoIP2               |            | ✔️         |             | ✔️          |
| Headers More         |            |            |             | ✔️          |
| Embedded Lua         |            |            |             | ✔️          |
| HTTP Substitutions   |            | ✔️         |             | ✔️          |
| Nchan                |            |            |             | ✔️          |
| Upload Progress      |            |            |             | ✔️          |
| Upstream Fair Queue  |            | ✔️         |             | ✔️          |


We hope you find this session informative and engaging. Stay tuned for more sessions in this Nginx tutorial series.
