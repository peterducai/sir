# sir

SIR is very "simple image registry" for OCI-compliant images, with basic RBAC

# GET

> go get github.com/peterducai/sir

# RUN

```sh
sir serve
```
to serve default **~/.local/share/containers/storage/** or **/var/lib/containers** (if run under ROOT)

```sh
sir serve imagedir=/mydir
```

# USE

```sh
sir push 