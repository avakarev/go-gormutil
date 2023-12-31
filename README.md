# gormutil

> Opinionated utilities for Gorm

# NOTE: deprecated, merged into https://github.com/avakarev/go-util
> Scheduled for deletion after 2023-09-1

## Requirements

gormutil includes

* ModelBase
    - primary key named `ID` and is in [uuid](https://github.com/google/uuid) format
    - assumes each model has `CreatedAt` and `UpdatedAt` timestamps
* Logger
    - backed by [zerolog](https://github.com/rs/zerolog)
    - respects `LOG_LEVEL` environment variable
* Data Import/Export
    - Exports filterable tables into `map[string]interface{}`
    - Imports from `map[string]interface{}`
* Create/Update helpers with respect of [validation](https://github.com/go-playground/validator) rules

## Install

```shell
go get github.com/avakarev/go-gormutil
```


## License

`go-testutil` is licensed under MIT license. (see [LICENSE](./LICENSE))
