# Docker Demystified

_Ian Johnson_

---

# What is Docker?

Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. Because all of the containers share the services of a single operating system kernel, they use fewer resources than virtual machines.

---

# But Why?

- Docker makes it easy for us to isolate environments and declare dependencies.
- Docker makes our applications portable and predictable.
- Docker allows us to have development parity as close to production to as possible. e.g., sqlite and postgres
- Docker allows us to update our dependencies in a dependable way.

---

# Important Concepts

### Images

- Images are built in layers.
- Images are built using a Dockerfile.
- `docker build`

---

# Important Concepts

### Containers

- Containers are executing instances of images.
- Containers executed using an image and a command.
- `docker run|exec`

---

# Important Concepts

### Orchestration

- Orchestration is the management of containers so that they can work in tandem.
- Orchestration is network level, but developer friendly.
- Kubernetes is a super-duper example of this.
- We do this locally during development using Docker Compose.
- `docker-compose build|up|down`

---

# But How Does It Work?

### 🐉

---

# Demo Time

What could go wrong?

---

# Now What?

- Take a look through the repositories and look at the `Dockerfile` and the `docker-compose.yml` files.
- Build the thing
- Prototype
- Kill it with fire
- Rebuild it from scratch

---

# Tips

- When running into an error ask yourself, "where is the origin of this error"?
- Use the logs!
