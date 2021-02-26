

<a href="https://www.powerconembedded.com/">
<img src="https://usercontent.one/wp/www.powerconembedded.com/wp-content/uploads/2017/06/2bigPowerConEmbeddedLogoTransparent-2.png" width="468">
</a>

# psignal Snippets

This extension provides helpful snippet when using PowerCon Embedded psignal.

## Limitations

For now it only supports snippets, this means simple code samples that can help you to avoid writing boilerplate.
That means loading of dependencies via pmake.load or other means doesn't happen.

## Available snippets

### Datatypes

| Name          | Code |
| ------------- | ------------- |
| int8          | `psignal.datatypes.int8()` |
| uint8         | `psignal.datatypes.uint8()` |
| int16         | `psignal.datatypes.int16()` |
| uint16        | `psignal.datatypes.uint16()` |
| int32         | `psignal.datatypes.int32()` |
| uint32        | `psignal.datatypes.uint32()` |
| uint64        | `psignal.datatypes.uint64()` |
| real32        | `psignal.datatypes.real32()` |
| real64        | `psignal.datatypes.real64()` |
| bool          | `psignal.datatypes.bool()` |
| array         | `psignal.datatypes.array(basetype=,length=)` |

### Signal, blocks and Classes

| Name          | Code |
| ------------- | ------------- |
| Enum class    | `class enum_name(psignal.datatypes.enum):` |
| Input         | `self.add_input(name="input_name", datatype=)` |
| Output        | `self.add_output(name="output_name", datatype=)` |
| Dat           | `self.add_dat(name="dat_name", datatype=)` |
| param.param   | `self.add(param.param(name="param_name" , datatype=, defval=, minval=, maxval=))` |

## Change Log

### 0.0.2

* Added more helpfull prefix to help new users find datatype snippets.
* Added param snippet

### 0.0.1

* Introduced basic snippets for input, output, dat and all psignal datatypes such as real32 and bool.
