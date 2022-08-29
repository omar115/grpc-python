# grpc-python

This repo contains the simple implementation of grpc using python.

## Instructions

### Step-1: Clone the repo
### Step-2: Create a venv

### Step-3: install dependencies

### Step-4: execute the command below

```
python -m grpc_tools.protoc --proto_path=.  ./bidirecctional.proto --python_out=. --grpc_python_out=.
```

### Step-5: run server

```
cd example/
python3 unary_server.py

```

### Step-6: open a second terminal and run client server

```
python3 unary_client.py
```