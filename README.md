# SNEKS Virtual Environment Manager

## Overview
SNEKS is a simple Bash script for managing Python virtual environments and their dependencies. It allows you to create, activate virtual environments, and manage Python packages.

## Getting Started
To start using the SNEKS script, simply download it and give it execute permissions:


`chmod +x sneks`

Usage

The script supports several commands:

    * create [env_name]: Creates a new Python virtual environment.
    * use [env_name]: Activates an existing Python virtual environment.
    * freeze: Freezes the current environment's packages into requirements.txt.
    * thaw: Installs packages from requirements.txt into the current environment.
    * help: Displays help information about the script.

Examples

* Creating a new environment:

```
sneks create myenv
```

* Activating an environment:

```
sneks use myenv
```

* Freezing dependencies:

```
sneks freeze
```

* Installing dependencies:

```
sneks thaw
```

Requirements

    Bash
    Python 3
    pip

