# protoc-gen-go-xorm

将 proto 中的 enum 类型生成 xorm 中的字段，使其可以直接以字符串的形式在数据库中进行保存。

### Deps

- protoc
- protoc-gen-go

### Install

```bash
go install github.com/nfangxu/protoc-gen-go-xorm@latest
```

### Usage

@see [Makefile](./Makefile)

### Tests

```bash
make tests
```
