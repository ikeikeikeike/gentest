`gentest` generates test funcs for implementing an interface.

```bash
go get -u github.com/ikeikeikeike/gentest
```

Sample usage:

```bash
$ gentest 'f *File' io.ReadWriteCloser
// not implemented
func TestRead(t *testing.T) {}

// not implemented
func TestWrite(t *testing.T) {}

// not implemented
func TestClose(t *testing.T) {}
```

