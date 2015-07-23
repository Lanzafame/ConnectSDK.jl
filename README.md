# Connect

[![Build Status](https://travis-ci.org/Lanzafame/Connect.jl.svg?branch=master)](https://travis-ci.org/Lanzafame/Connect.jl)

## Installation

```julia
Pkg.add("Connect")
```

## Usage

```julia
using Connect

connect = ConnectClient(projectID, apiKey)

r = push(client, collection, data)

q = query(client, collection, query)

```
