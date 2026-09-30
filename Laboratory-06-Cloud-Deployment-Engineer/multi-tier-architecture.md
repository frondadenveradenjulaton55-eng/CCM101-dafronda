# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture consists of two separate but connected parts of an application. One part is responsible for handling the application and user interaction, while the other part manages the information stored by the system.

## The Web/Application Tier

The Web/Application Tier acts as the main point of interaction between the user and the application. It receives HTTP requests, processes application functions, and displays the appropriate interface to the user. In this deployment, Nextcloud is used for the Web/Application Tier.

## The Database Tier

The Database Tier manages the data required by the application and provides persistent storage. It is responsible for storing and retrieving information when requested by the application. MariaDB is used as the Database Tier in this deployment.

## Why Separate Them?

The web server and database are placed in two separate containers so that each one can concentrate on its own task. This separation makes it easier to manage, update, and troubleshoot the application and database independently. It also provides a clearer structure for communication between the two services.
