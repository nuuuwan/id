# Identity Platform (id)

This python library implements a server, which can be run as follows.  

```python
server = Server()
```

The server can be called from a client as follows. 

```python
client = Client()
client.message('a')
```

When a client messages the server in this way, the server logs the message. It also has a method of verifying who the client is. 