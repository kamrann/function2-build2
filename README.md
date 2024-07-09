# function2 - A C++ library

The `function2` C++ library provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `function2` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: function2 ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = function2%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.function2.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
